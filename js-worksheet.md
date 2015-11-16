####Name:
####ScriptEd
####Topic: JavaScript

* Explain what a function is. Give an example. A function is a code that performs a task.
* function sayHello(){
*   return "Hello!"
* }
* Explain what a parameter is. Give an example. A parameter is brackets that holds an arguement and part of local scope.
* function name(Anthony) {
*   return "Anthony!"
* }
* When we want to look up what a word means, we go to a dictionary. Similarly, when we want to look up what a standard JavaScript function does, we look at _______________ Console.
* In the following piece of code, what variable(s) are in scope at Point A, Point B, and 
Point C? A: 3, B: scope, C is nothing

```
var hooligan = true;

function hva() {
  var num = 3;
  // Point A
}

function rocks() {
  var str = "scope";
  // Point B
}

// Point C
```
* What does the following code print?

```
var x = 7;

function someFunction() {
  var x = 10;
  console.log("Inside the function, x is " + x);
}

console.log("Outside the function, x is " + x);
someFunction();
```

It prints Outside the function, x is 7 and Inside the function, x is 10.

* Write a function that returns the result of the following equation: 5a^2 + 4b + c. You should use the pow() function. Your function should take in three parameters (a,b,c).
function Math.pow (a,b,c){
  return 
####Some review
* Close this HTML element (remember HTML??): `<h2> My Books`</h2>
* What HTML element is used to create an **ordered list** of items?
*<ol></ol>
* Write a CSS rule that will make only the word *Adams* red:
`<span id="first">Washington </span><span id="second">Adams </span><span id="third>Jefferson</span>"`

span id=third {
  background-color: red;
}
