# Code Library

## Introduction

This challenge was submitted by Dave Lusty.

Most modern programming languages allow the creation of some sort of library of functions, allowing you to reuse your code while keeping a centrally tested and up to date version.

This will be applicable for both programming and machine learning scenarios among others. There are various aspects to this challenge, and these will include:

* Code versioning
* Building a library deliverable
* Testing the function (Unit testing)
* Storing the library somewhere accessible, such as an object repository
* Retrieving the library for use within another project

## Instructions

### The Library

There are many languages and many products you can use for this challenge, so please pick the ones you like best and create your solution. To get you started, your function library should contain two functions detailed below. Obviously these probably already exist in your language of choice, they are just there to form the basis of your challenge.

**add(x, y)**
This takes two numbers and returns the sum of them

**uppercase(word)**
This takes a string and returns the uppercase version of it.

### Testing

You should run various tests against your functions including passing incorrect data types in, and passing in out of bounds variables such as very large numbers (above 32 bit for instance) or very long strings (over 255 characters). Record the output of these tests in your release pipeline.

### Publishing

You should then push your package to somewhere your project can use it. 

## Hints

If you're stuck, you may like to try this with Azure DevOps, GitHub, Azure Pipelines, and Azure Artifacts. 

For your language, machine learning specialists may use Python to create an Egg or wheel. Programmers may want to create a Java JAR, or a .net library. You may also wish to make a PowerShell module for scripting.

## Outcomes

You should be able to add a function to your library, commit the code and have your solution automatically build, test, and publish that library.