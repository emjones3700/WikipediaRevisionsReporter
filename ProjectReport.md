# Project Report

Emma Jones

 

## Challenge #1 Complete

In the Guice config class QueryEngineModule, I changed the binding from FakeQueryEngine.class to WikipediaQueryEngine.class

## Challenge #2 Complete

I started by making a generic Formatter interface that is implemented by the original RevisionFormatter and my added NewAndImprovedRevisionFormatter. In my new formatter, I 
revise the DateTimeFormatter to show non-military time and ISO dates for a better user experience.

## Challenge #3 Complete
To make the string in one line, I used the reduce function in Java's Stream API to append the results.
## Reflection Question #1: Functional vs OO

At first, I thought I preferred the itterative approach to string concatenation over the functional one, however I think I might like the functional approach better. The functional approach does not take up as much space, but can be a little confusing to look at while the itterative approach is less concise but easier to understand. I am  more used to the iterative approach, but would like to try the functional way more in the future. 
## Reflection Question #2: Polymorphism and Dependency Inversion

In this project, polymorphism is used by my Formatter interface through dependency inversion. The general interface can be referenced by lower level structures throughout the project instead of having to build around each individual formatter.
