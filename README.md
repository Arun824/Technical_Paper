# JavaScript 
**Introduction :** JavaScript is the Programming Language for the Web. it can allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps etc.

## Data and Structure types of javaScript
JavaScript has a different data type which is the following.  


**1. Primitive data type**  

|Data Type | Description | 
|:---------|:------------|
| Strings    | represents sequence of characters e.g. "Arun" |
| Number | represents numeric values such as 16 |
| Boolean |represents boolean value either false or true |
| Undefined | represents undefined value |
| Null    |  represents null i.e. no value at all |




## JavaScript Strings
A string is a series of characters like "Arun Kumar".  
Strings are written with quotes. You can use single or double quotes.

*Example :*      
```
var answer1 = "It's alright";          // Single quote inside double quotes

var answer2 = "He is called 'Johnny'";    // Single quotes inside double quotes

var answer3 = 'He is called "Johnny"';    // Double quotes inside single quotes
``` 
To know more about string   
[click here](https://www.w3schools.com/js/js_strings.asp)
   

## JavaScript Number   
JavaScript has only one type of numbers.

Numbers can be written with, or without decimals:

*Example :* 

```
var x1 = 34.00;// Written with decimals
var x2 = 34; // Written without decimals
```
Extra large or extra small numbers can be written with scientific (exponential) notation:   
*Example :* 
``` 
var y = 123e5;      // 12300000
var z = 123e-5;     // 0.00123  
```   
To Know more about Number   
[click here](https://www.w3schools.com/js/js_numbers.asp)
## JavaScript Boolean
JavaScript Boolean represents only two value either true or false.

*Example :* 
 ```
 function myFunction(x, y, str) {
     
     console.log(Boolean(x)); // false
     console.log(Boolean(y)); // true
     console.log(Boolean(str)); // true
 }
 let x = 0;
 let y = 1;
 let str = "Arun";
 myFunction(x, y, str);   
 ```   
 To know more about Boolean   
[click hare](https://www.w3schools.com/js/js_booleans.asp)

 ## JavaScript Undefine
 A variable that has not been assigned a value has the value undefined.

  *Example :*     

  ```
  var car;    // Value is undefined, type is undefined
  ```    
  Any variable can be emptied, by setting the value to undefined. The type will also be undefined.  
  *Example :*  
  ``` 
 car = undefined;    // Value is undefined, type is undefined
  ```    
  To know more about Undefine   
  [click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined)
  ## JavaScript Null
  In JavaScript null is "nothing".   
  It is supposed to be something that doesn't exist.    
Unfortunately, in JavaScript, the data type of null is an object.

*Example :
```
function getVowels(str) {
  const m = str.match(/[aeiou]/gi);
  if (m === null) {
    return 0;
  }
  return m.length;
}

console.log(getVowels('sky'));
```    
*output :* 0  

To know more about Null         
[click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null)

**2. Non-primitive data types**  

| Data Type  | Description |
| :----------| :-----------|
| Object     | represents collection of properties |
| Array   | represents group of similar values |
| RegExp  | represents regular expression |

## JavaScript Object 
An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method.

```
var person = {
  firstName: "Arun",
  lastName: "Singh",
  age: 24,
  eyeColor: "black"
};
```
Here person is an Object.   

**Object Properties**      

The name:values pairs in JavaScript objects are called properties:    
| Property | Property Value |
| :--------| :--------------|
| firstName | Arun |
| lastName  | Singh |
|  age    | 24 |
| eyeColor  | black |

**you can access object properties in two ways:**   
```
objectName.propertyName
```
or
```
objectName["propertyName"]
```
*Example :* 
``` 
person.lastName;
```  
*output :* Singh    
To know more about Object   
[click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)    


## JavaScript Array 
JavaScript array is an object that represents a collection of similar type of elements.    

*Example :*
``` 
var colors = ["red","blue","green"];

for (var i = 0; i < colors.length; i++) {
    console.log(colors[i]);
}
```
*output :* red, blue, green    

**Creating an Array**   
Using an array literal is the easiest way to create a JavaScript Array.     
*Syntax :*  
 ``` 
 var array_name = [item1, item2, ...];   
 ```
  *Example :*    
  ```  
  var cars = ["Saab", "Volvo", "BMW"];
  ```    
  To know more about Array    
  [click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
  ## JavaScript RegExp      

  A regular expression is an object that describes a pattern of characters.      
  Regular expressions can be used to perform all types of text search and text replace operations.    

  *Syntax :* 
```      
/pattern/modifiers;
 ```     
*Example :*     
Use a string to do a search for "singh" in a string:      
```  
var str = "Arun singh";
var n = str.search("singh");
console.log("Position of serch element is " + n);
```   
*output :* Position of serch element is 5        

To know more about RefExp     
[click here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)

 # ECMAScript 2015 - ES6 
 **Introduction :**  ES6 stand for ECMAScript  which is refers to version 6 of the ECMA Script programming language
It is a major enhancement to the JavaScript language, and adds many more
features intended to make large-scale software development easier.  

## Some New Features in ES6
[The let keyword](https://www.w3schools.com/js/js_es6.asp#mark_let)   
[The const keyword](https://www.w3schools.com/js/js_es6.asp#mark_const)    
[JavaScript Arrow Function](https://www.w3schools.com/js/js_es6.asp#mark_arrow)      
[JavaScript For/of](https://www.w3schools.com/js/js_es6.asp#mark_forof)  
[Array.find()](https://www.w3schools.com/js/js_es6.asp#mark_array_find)    
[JavaScript Promises](https://www.w3schools.com/js/js_es6.asp#mark_promise)

## JavaScript Let  
The let keyword allows you to declare a variable with block scope.

*Example :* 
```
var x = 10;
// Here x is 10
{
  let x = 2;
  // Here x is 2
}
// Here x is 10 
```   
## JavaScript const   
The const keyword allows you to declare a constant.
*Example :* 
```
var x = 10;
// Here x is 10
{
  const x = 2;
  // Here x is 2
}
// Here x is 10 
```
## Arrow Functions
Arrow functions allows a short syntax for writing function expressions.

You don't need the function keyword, the return keyword, and the curly brackets.   
*Example :*
```
// ES5
var x = function(x, y) {
   return x * y;
}

// ES6
const x = (x, y) => x * y;
```

## The For/Of Loop
The JavaScript for/of statement loops through the values of an iterable objects.

for/of lets you loop over data structures that are iterable such as Arrays, Strings, Maps, NodeLists, and more.

The for/of loop has the following syntax: 
```
for (variable of iterable) {
  // code block to be executed
} 
```
**Looping over an Array**  
*Example :*  
```
var cars = ["BMW", "Volvo", "Mini"];
var x;

for (x of cars) {
  console.log(x);
} 
```
*output :* "BMW", "Volvo", "Mini" 

## Array.find()   
The find() method returns the value of the first array element that passes a test function.   
*Example :* 
```
var numbers = [4, 9, 16, 25, 29];
var first = numbers.find(myFunction);
console.log("First number over 18 is " + first);
function myFunction(value, index, array) {
  return value > 18;
}
```
*output :*  First number over 18 is 25  

## JavaScript Promises
A Promise is a JavaScript object that links "Producing Code" and "Consuming Code".  
"Producing Code" can take some time and "Consuming Code" must wait for the result.  

**Promise Syntax**  
``` 
let myPromise = new Promise(function(myResolve, myReject) {
// "Producing Code" (May take some time)

  myResolve(); // when successful
  myReject();  // when error
});

// "Consuming Code" (Must wait for a fulfilled Promise).
myPromise.then(
  function(value) { /* code if successful */ },
  function(error) { /* code if some error */ }
); 
```   
**Example Using a Promise** 
```
let myPromise = new Promise(function(myResolve, myReject) {
  setTimeout(function() { myResolve("I love You !!"); }, 3000);
});

myPromise.then(function(value) {
  document.getElementById("demo").innerHTML = value;
}); 
```
**Reference**     
To Learn JavaScript And ES6 in deeply [click](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

 