# daily-javascript-q91

An HTML page contains the following: 

``` html
<div id="result"></div> 
<script> 
//Add code here 
</script> 
```
You need to add code to the <script> tag so that the current date is displayed on the screen and refreshed every second. 

Which code snippet should you use?
<hr>
Choose the correct answer

Option 1:
```javascript
setInterval(function() {
     let d = new Date();
     document.getElementByClassName("result").innerHTML = d;
}, 1000);
```
Option 2:
```javascript
setInterval(function() {
     let d = new Date();
     document.getElementById("result").innerHTML = d;
}, 10000);
```
Option 3:
```javascript
setInterval(function() {
     let d = new Date();
     document.getElementById("result").innerHTML = d;
}, 1000);
```
Option 4:
```javascript
function printDate() {
     for (var i = 1; i <= (24*60*60); i++) {
          let d = new Date();
          document.getElementById("result").innerHTML = d;
      }
}
printDate();
```
