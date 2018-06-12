## Challenge

A console application that takes in an argument at command line (1d6, 2d6, 3d20, etc), simulates a dice roll, and logs the value on console.

## Learning Outcomes
* Functions
* Array Handling
* String manipulation 
* Handling different types of data 
* How console arguments work
* Built-in JavaScript objects 

## Expected Outcome 

The user should be able to type in the following: 

`node roll.js <dice configuration>`

and return the value rolled from the simulated dice on the console in the following form: 

```
$ node roll.js 1d20
1d20: 15

$ node roll.js 1d6
1d6: 4

$ node roll.js 1d8
1d8: 7

$ node roll.js 3d10000
3d10000:  19803

```

The dice configuration value can be as simple as 1d6 or be as absurd as 1000d20. Your code must be able to handle both cases.

## Remember

* You are writing your code for others, not just yourself
* Make sure your code is presentable and readable
* Use variable names that are easily understood
* Include comments where you feel your intent is not easily conveyed by variable names and code structure alone 

## Resources
* You don't need any extra libraries. What vanilla JavaScript and the NodeJS Environment provides is sufficient to complete this task
* NodeJS's [process.argv](https://nodejs.org/docs/latest/api/process.html#process_process_argv) array 
* [Arrays](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
* Take a look at String Methods at [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and [W3Schools](https://www.w3schools.com/Js/js_string_methods.asp)
* Take a look at Number Methods at [MDN]() and [W3 Schools](https://www.w3schools.com/Js/js_number_methods.asp);
* [JavaScript's Math object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math) 
* Functions on [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
