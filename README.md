<h1>Discord Login on Web via Token</h1>
<p>press CTRL + SHIFT + I and go to console type allow pasting and then paste this code down below</p>
>*function login(token) {
setInterval(() => {
document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
}, 50);
setTimeout(() => {
location.reload();
}, 2500);
}

login('PASTE TOKEN HERE')<*
