## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div
```
let firstNumber = Number(prompt('Enter number one'));
let secondNumber = Number(prompt('Enter number two'));
let operation = prompt('Enter operation to perform, + for add, - for substract, * for multiplication and / for division');
if (operation == '+'){
  let finalSum = firstNumber + secondNumber;
  alert(finalSum)
}
if(operation == '-'){
 let substraction = (firstNumber > secondNumber) ? (firstNumber-secondNumber) : alert('Enter valid number');
 alert(substraction)
 }
if(operation == '*'){
  let multiply = firstNumber * secondNumber;
  alert(multiply);
}
if(operation == '/'){
  let division = (firstNumber > secondNumber) ? (firstNumber/secondNumber) : alert('Enter valid number');
}
```

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
if(firstName == status){
  console.log(`${firstName} is ${status}`)
}else{
  console.log(`${firstName} is married`);
}
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
let numberOne = propmt('Enter Number');
let numberTwo = prompt('Enter second number');
if(numberOne > numberTwo){
  alert(`${numberOne} is larger`)
}else{
  alert(`${numberTwo} is larger`);
}
// your code goes here
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
let numberOne = Number(prompt('Enter number one'));
let numberTwo = Number(prompt('Enter number two'));
let numberThree = Number(prompt('Enter number three'));
let total = numberOne + numberTwo + numberThree;
if(total > 0 ){
  alert(`${total} is positive number`)
}else if(total < 0){
  alert(`${total} is negative number`);
}
// Your code goes here
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
let numValue = Number(prompt('Enter Number'))
switch(numValue) {
  case(1) : alert('ONE')
  break;
  case(2) : alert('TWO')
  break;
  case(3) : alert('THREE')
  break;
  case(4) : alert('FOUR')
  break;
  case(5) : alert('FIVE')
  break;
  case(6) : alert('SIX')
  break;
  case(7) : alert('SEVEN')
  break;
  case(8) : alert('EIGHT')
  break;
  case(9) : alert('NINE')
  break;
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
var marks = Number(prompt("enter your marks"));
switch(marks) {
  
  case(marks>90): alert("AA");
  break;

  case((marks<=90) && (marks>80)): alert("AB");
  break;

  case((marks<=80) && (marks>70)): alert("BB");
  break;

  case((marks<=70) && (marks>60)): alert("BC");
  break;

  case((marks<=60) && (marks>50)): alert("CC");
  break;

  case((marks<=50) && (marks>40)): alert("CD");
  break;

  case((marks<=40) && (marks>30)): alert("DD");
  break;

  case(marks>30): alert("FF");
  break;

  default: alert("Fail");
}
```