# JAVASCRIPT NOTES

> OPERATOR IN JAVASCRIPT

1. ARTIMETIC OPERTOR [ +,-,*,/,% ]

````js
let a=5;
let b=2;

console.log("a + b = ",a+b);    //sum
console.log("a + b = ",a**b);   //power
````

2. UNARY OPERTOR [ a++,a--,++a,--a ]

````js
let a=5;
console.log("before increant:")
console.log("a : ",a);
console.log("after increant:")
a++;
console.log("a : ",a);
````

3. ASSIGNMENT OPERATOR [ =,+=,-=,*=,/=,**=]

````js
let a = 5;

{   a += 10;            // a = a + 10
    console.log(a);
}

{   a -= 10;            // a = a - 10
    console.log(a);
}

{   a *= 10;            // a = a * 10
    console.log(a);
}

{   a /= 10;            // a = a / 10
    console.log(a);
}

{   a **= 2;           // a = a ** 2
    console.log(a);
}
````
4. COMPARSION OPERATOR
    
    * Equal to  (==)
    * Equal to and Type  (===)
    * Not Equal to (!=)
    * Not Equal to and Type (!==)
    * (>, >=,<,<=)

<b>note:</b> generaly we use === and !== .

````js
let a = 10;     //Number
let b = "10";   //string

console.log("a == b : " , a == b );     //Only check Value
console.log("a === b : " , a === b );   //Only check Value and Type

console.log("a != b : " , a != b );     //Only check Value
console.log("a !== b : " , a !== b );   //Only check Value and Type
````

5. LOGICAL OPERTORS

    * Logical AND ( && )
    * Logical OR ( || )
    * Logical NOT ( ! )

6. TERNARY OPERATORS

    * condition ? true output : false output

````js
age = 25;

age > 18 ? console.log("your 18+") : console.log("your not 18+");
````

> CONDITIONAL STATEMENTS  

````js
age = 25;

if(age < 18){
    console.log("junior");
}
else if(age > 60){
    console.log("Senior");
}
else{
    console.log("Middle");
}
````

----

<b>note :</b>

* To connect js to html code in head tag or html tag inside

````
<script src="script.js"></script>
````


* The alert() method in JavaScript is used to display a virtual alert box

````js
alert("1 hello world");
//or
window.alert("2 hello world");
````

* Prompt( ) dialog box with the message “Please enter your name” and a default input value of “Harry Potter”. The value entered by the user will be stored in the variable

````js
// Get user to input a number using prompt("Enter a number:"). Check if the number is a multiple of 5 or not.

let num = prompt("Enter a number:");

if(num%5 === 0){
    console.log("number is multiple of 5");
}
else{
    console.log("number is not multiple of 5");
}
````