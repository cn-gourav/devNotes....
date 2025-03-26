# Functions in Java

Functions are blocks of code that help avoid repetition. Here's a quick guide to working with functions in Java:

## How to Create a Function

```javascript
function name() { 
    // Write code here
}

name(); // Function call

```
## Examples
```javascript
1. Add Two Integers
java
function add() {
    console.log(2 + 2);
}

add();
2. Multiply Two Integers
java
function multiply(a, b) {
    console.log(a * b);
}

multiply(2, 2);
3. Generate a Multiplication Table
java
function table(a) {
    for (let i = 1; i <= 10; i++) {
        console.log(a * i);
    }
}

table(2);
4. Check if an Adult
java
function adult(age) {
    if (age >= 18) {
        console.log("adult");
    } else {
        console.log("not adult");
    }
}
```
```javascript

adult(20);
Functions with Arguments
java
function name(parameter1, parameter2, ...) {
    // Write code here
}

name(argument1, argument2, ...); 
```

# Understanding the `return` Keyword in JavaScript

The `return` keyword in JavaScript is used within functions to specify the value that the function should output when it's called. When a function executes the `return` statement, it immediately stops and exits, returning the specified value to the caller. This allows functions to produce results that can be used elsewhere in the program.

## Example of `return`
```javascript
function add(a, b) {
    return a + b; // Returns the sum of a and b
}

let result = add(5, 3); // Calls the function and stores the result
console.log(result); // Outputs: 8
```
# Key Points
The return keyword can be followed by any value, including variables, expressions, objects, arrays, etc.

A function without a return statement will return undefined by default.

Once the return statement is executed, the function ends and no further code within that function will run.

Example:

```javascript
function example() {
    return "This ends the function!";
    console.log("This will not be executed.");
}