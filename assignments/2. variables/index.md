1. In code below "Mark" is a string. What is name?

```js
var name = "Mark";
//variable name.
```

2. Find the error if any

```js
  var product cost = 3.45;
  // variable name cannot be written with spaces between.
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //right;
  'Hello World" //wrong;
  "Hello World' //wrong;
  'Hello World' //right;
```

## Write `VALID` and `INVALID` infront of the variable name defined below

```js
var man; //valid
var 1girl;  //invalid
var woman3; //valid
var -girl;  //invalid
var blackDog; //valid
var 42; //invalid
var $42;  //valid
var userName; //valid
var x, y, z;  //valid
var x = 5, y = 6, z = 7;  //valid
var x = 5 + 10 + 2; //valid
var user = "Tyrion"; "Arya"; "John"; //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, \*, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
let lessThan = amount - 80;

// Define a new variable and store the value that is 200 more then the value of amount.
let moreThan = amount + 200;

// Define a new variable and store the value that is 4 times the value of amount.
let moreThan = amount*5;

// Define a new variable and store the reminder when the value of amount is  divided by 21.
let remainderValue = amount % 21;
```

## var, let and const

Write down the code or if there is any error write down the error.

```js
var user = "Sameer";

// Reassign the value of user to "Sam"
let newUser = "Sam";
user = newUser;

// Define a variable with name user with value "Irfan"
let newName = "Irfan";

let number = 21;
// Reassign the value of number to 60
let newNumber = 60;
number = newNumber;

// Define another variable called number with the value of 100
let number = 100;

const username = "Admin";
// Reassign the value of username to "Arya"
cannot reassign the value to a const.

// Define a variable called usernae with value "John"
let username = "John";
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
let newAge = (johnAge > markAge) ? johnAge : markAge;

// Check who is younger
let youngAge = (johnAge > markAge) ? markAge : johnAge;

// Check if their age is equal
let ageEqual = (johnAge == markAge) && (johnAge < markAge);

// Create a new variable and assign the age of john to new variable.
johnAge = newPerson;

// Check if john is equal to or greater then mark.
let johnEqual = johnAge >= markAge ? true : false;

// Check if john is less then or equal to mark.
let johnEqual = (johnAge =< markAge) ? true : false;

// Calculate the average age of john and mark and assign to a new variable.
let averageAge = johnAge + markAge;
console.log(averageAge/2);
```