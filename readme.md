# Functions in Java

Functions are blocks of code that help avoid repetition. Here's a quick guide to working with functions in Java:

## How to Create a Function

```java
function name() { 
    // Write code here
}

name(); // Function call

-Examples

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

adult(20);
Functions with Arguments
java
function name(parameter1, parameter2, ...) {
    // Write code here
}

name(argument1, argument2, ...);