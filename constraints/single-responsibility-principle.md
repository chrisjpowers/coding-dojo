# Single Responsibility Principle

The Single Responsibility Principle states that every class, module, and function should have a single responsibility. To put it another way, each structure in your code should change for only one reason.

## The Constraint: Take It Further!

We all have a general sense of how big or small our code modules should be, but for this exercise we are going to take the Single Responsibility Principle to the extreme!

* If you are using Object Oriented Programming, use many small classes with very focused jobs.
* If you are using Functional Programming, compose tiny functions into higher order functions to keep responsibilities separated.
* Use unit tests to ensure the implementation is correct and you haven't regressed during refactoring.

## Discussion Questions

* What happens when you decompose your classes... and keep going?
* How small can you make them?
* How singular can their responsibilities be?
* What happens to your tests when your modules are small?
* When modules are very small, what are the benefits?
* What pain points come from writing code like this?
* What can we learn from this exercise?