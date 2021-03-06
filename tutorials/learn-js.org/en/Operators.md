Tutorial
--------

Every variable in JavaScript is casted automatically so any operator between two variables will always give some kind of result. 

### The addition operator

The `+` (addition) operator is used both addition and concatenation of strings.

For example, adding two variables is easy:

    var a = 1;
    var b = 2;
    var c = a + b;     // c is now equal to 3

The addition operator is used for concatenating strings to strings, strings to numbers, and numbers to strings:

    var name = "John";
    console.log("Hello " + name + "!");
    console.log("The meaning of life is " + 42);
    console.log(42 + " is the meaning of life");

### Mathematical operators

To subtract, multiply and divide two numbers, use the minus (`-`), asterisk (`*`) and slash (`/`) signs.

    console.log(3 - 5);     // outputs -2
    console.log(3 * 5);     // outputs 15
    console.log(3 / 5);     // outputs 0.6

### Advanced mathematical operators

JavaScript supports the modulus operator (`%`) which calculates the remainder of a division operation.

    console.log(5 % 3);     // outputs 2

JavaScript also has a `Math` module which contains more advanced functions:

* `Math.abs` calculates the absolute value of a number
* `Math.exp` calculates __e__ to the power of a number
* `Math.pow(x,y)` calculates the result of __x__ to the power of __y__
* `Math.floor` removes the fraction part from a number

And many more mathematical functions.

Exercise
--------

In this exercise, you do the following:

1. Connect the `firstName` and `lastName` to construct the variable `fullName`, but with a space (`" "`) in between the first and last name.
2. Multiply the variable `myNumber` by 2 and put the result in `meaningOfLife`.

Tutorial Code
-------------

var firstName = "John";
var lastName = "Smith";
var myNumber = 21;

// TODO: change the following code
var fullName = null;
var meaningOfLife = null;

console.log("The name is " + fullName);
console.log("The meaning of life is " + meaningOfLife);

Expected Output
---------------

The name is John Smith
The meaning of life is 42

Solution
--------
