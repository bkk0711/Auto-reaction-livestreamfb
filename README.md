# Auto-reaction-livestreamfb
```
var reactInterval = setInterval(function () {
if ( document.getElementsByClassName('_iuw').length ) {
var rand_number = Math.floor(Math.random() * 3);
document.getElementsByClassName('_iuw')[rand_number].click();
console.log("reaction "+rand_number);
} else {
console.log('React button not found');
clearTimeout(reactInterval);
}
}, 1000);
```
* F12 -> Console 
