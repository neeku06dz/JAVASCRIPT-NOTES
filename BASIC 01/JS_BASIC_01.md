# JAVASCRIPT NOTES
````js
console.log("hello world");     //TO PRINT
````

## Variable in js

````js
name = "neeraj kumar";  //String
age = "22";             //Number
price = "22.22";        //
isfollow = true;        //Boolen
y = undefined;          //Undefined
a = null;               //NULL
````
![](https://www.learnsimpli.com/wp-content/uploads/2019/09/javascript-data-types.png)

**Note:** – js is dynamic typed language

>let, const & var

- var: Variable can be re-declared & updated. A global scope variable.

````js
//can be re-declared & updated variable
var age = 22;
var age = 23;
var age = 24;
````
- let: Variable cannot be re-declared but can be updated. A block scope variable.

````js
//can not be re-declared & updated variable
let age = 22;
let age = 23;
let age = 24;
````

````js
//if let variable is empty by default by is undefined
let name;
````

- const: Variable cannot be re-declared or updated. A block scope variable.

````js
//const variable conn't be empty
const name;     //error
````
