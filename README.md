# findPos()
JS function to find the true position of an element, relative to the page (regardless of scroll position). Code taken straight from http://www.quirksmode.org/js/findpos.html, all credit to PPK.

## Usage

```
var myEl = document.createElement('div');
myEl.style.top = '100px';
myEl.style.top = '100px';
document.body.appendChild(myEl);

var myElPos = findPos(myEl); // [200, 200]
```
