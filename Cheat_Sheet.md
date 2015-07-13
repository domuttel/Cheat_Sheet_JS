#Cheat Sheet

##5 Primitives:

1. Strings
1. Numbers
1. Booleans
1. Undefined
1. Null

##String Concatenation:

(+) ; adds strings together

##Functions:

*Parameters are the functions for both Declarations and Expressions*

###Declaration functions- can be called from anywhere (global):



      function foo() {
      return 5;
      }

      foo();
      ->

###Expression functions (global):

      var foo = function() {
      return 5;
      }

      foo();
      ->


calling the function is the = argument

##Loops:

###for loop:

ex. 2

      var result = 1;
      for (var counter = 0; counter < 10; counter = counter + 1) {      result = result * 2; console.log(result); }

       → 1024
ex. 2

      for (var current = 20; ; current++) {
      if (current % 7 == 0)      break; }      console.log(current);
      → 21



###while loop:

ex. 1

    var number = 0;      while (number <= 12) {      console.log(number);      number = number + 2; }
      →

ex. 2

    var result = 1;    var counter = 0;    while (counter < 10) {    result = result * 2;    counter = counter + 1;    } console.log(result);
   → 1024

##Conditionals:

###if statements:

      var theNumber = Number(prompt("Pick a number", ""));

      if (!isNaN(theNumber)) {      alert (" Your number is the square root of " + theNumber * theNumber);      } else {      alert("Hey. Why didn't you give me a number?");
      }
      //


##Variables
ex. 1

    var variableTitle = X
    var c = 10;
    console.log(c * c);
    -> 100
ex. 2

    c = 5
    console.log(c * c)
    -> 25

##Alerts and Prompts:

###Alert:

document.window.alert(“”)

window.alert(“”)

alert(“”)

###Prompt:

document.window.prompt(“”)

window.prompt(“”)

__ prompt(“”) __


##Scope

###Global Variable:

      var global = X

      [function here]

###Local Variable:

      [function
      var local = X]

##Operators

###Math Operators:

+, -, *, /, and %

###Comparisons Operators:

==, !=, ===, !==, <, >, <=, >=

###Logic Operators:

&&, ||

##Methods: String, Integers
