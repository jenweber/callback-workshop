[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Callback Workshop

Why learn about callbacks? Callbacks give you more options for organizing your code and making it readable to others. You'll have have finer control over what-happens-when as a script executes. If you get comfortable using callbacks now, you'll have a much easier time when you are tackling more complex projects and integrating server requests.

## Prerequisites

-   Your lessons earlier today

## Objectives

By the end of this, developers should be able to:

-   Write a function that takes another function as an argument.
-   Call that function, passing in arguments.
-   Explain in their own words what a callback is.
-   Give an example of a time that a callback may be useful.


## Preparation

1.  Fork and clone this repository
1.  Be ready to take notes

## What is a callback?

Before we get into callbacks, let's review some basics of functions. You already know how to write a regular function:
```
const simpleAddition = function() {
  return 1 + 2;
}
```
And you know how to write a function that takes arguments:
```
const argAddition = function(a, b) {
  return a + b;
}
```
How would you call the function above? What if you wanted to pass in variables instead of numbers?
```
let bankAccount = 5;
let newSalary = 65000
```
Just like you can pass variables into a function, you can pass a function into a function too! When this happens, that's what we refer to as a callback.

A callback is a label that describes a function that's passed into *another* function as an argument.

## Demo: Whiteboard Callbacks

Demos are demonstrations, and developers should give their full attention to
them. It's a great time for them to take notes about important concepts before
applying them in an exercise.

Demos correspond to the "I do" portion of scaffolding from consultant trainging.

## Exercise: Write an Exercise

During exercises, developers should apply concepts covered in the previous demo.
This is their first chance to generalize concepts introduced. Exercises should
be very focused, and flow natural into a lab.

Exercises correspond to the "We do" portion of scaffolding from consultant
trainging.

## Lab: Write a Lab

During labs, developers get to demonstrate their understanding of concepts from
demos and applied knowledge from exercises. Labs are an opportunity for
developers to build confidence, and also serve as a diagnostic tool for
consultants to evaluate developer understanding.

Labs should be timed explicitly using a timer. When estimating the time it will
take to complete a lab, it is better to overestimate. During labs, consultants
should circle the room and interact with developers, noting patterns and
prompting with hints on how to complete the lab. If developers end early, a
consultant may stop the lab timer. If developers do not finish in time, a
consultant may give more time at her discretion based on current talk pace, the
current estimate for the talk, and the importance of completing the lab while
consultant support is available.

Labs correspond to the "You do" portion of scaffolding from consultant
trainging.

## Additional Resources

-   Any useful links should be included in the talk material where the link is
    first referenced.
-   Additional links for further study or exploration are appropriate in this
    section.
-   Links to important parts of documentation not covered during the talk, or
    tools tangentially used but not part of the focus of the talk, are also
    appropriate.

## [License](LICENSE)

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
