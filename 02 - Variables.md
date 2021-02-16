### Understanding let, var and const.
```javascript
  var example1;            // var variables have global scope.
  let example2;            // let variables have restricted scope.
  const name = "Leonardo"; /* const variables also have restricted scope, cannot be
                              reassigned and need to be initialized with a value. */
```
### Declaring a variable.
```javascript
  var city;
  let age;
  const name = "Leonardo";  //const variables needs be initialized with a value
```
### Storing a value in a variable.
```javascript
  city = "Ribeirão Preto;
  age = 23;
```
### Initializing a variable with an assigned value.
```javascript
  let hairColor = "black";
```
### Understanding uninitialized variables.
```
  When JavaScript variables are declared, they have an initial value of undefined. 
If you do a mathematical operation on an undefined variable your result will be NaN 
which means "Not a Number". If you concatenate a string with an undefined variable, 
you will get a literal string of "undefined". */
```
### Understanding Case Sensitivity in Variables.
```
  In JavaScript all variables and function names are case sensitive. This means that
capitalization matters, MYVAR is not the same as MyVar nor myvar.
       
  Is a good practice write variable names in JavaScript in camelCase. In camelCase, 
multi-word variable names have the first word in lowercase and the first letter of
each subsequent word is capitalized. 
```
