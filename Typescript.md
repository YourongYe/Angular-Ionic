# Promises
```js
var promiseObj = new Promise(executor);
executor = function(resolutionFunc, rejectionFunc){
    // typically, some asynchronous operation.
}
```

# Callback (functions)
A function passed as argument to a function is called a callback function  
```js

function add(a, b , callback){ 
   document.write(`The sum of ${a} and ${b} is ${a+b}.` +"<br>"); 
   callback(); 
   } 
     
// disp() function is called just 
// after the ending of add() function  
function disp(){ 
  document.write('This must be printed after addition'); 
  } 

// Calling add() function 
add(5,6,disp); 
```
