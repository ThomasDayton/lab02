# Lab 02 -- Chapter 01

## Define the followint terms:
* object, --An Object is an instance (state or behavior) of a class.
* class, --a Blueprint (code) that defines how to create an object.
* instance, --A specific realization of any object.
* method, --A collection of statements, in a class, that can be used to manipulate (mutators) or access information (accessor) from an object of that class. (Behaves like a function)
* signature, --The name of a method and the parameter types found in its header. (Ex. void changeSize(Box box) changes the size of instance "box" of class "Box" and does not give an output)
* parameter, --An input of the method. (Ex. "box" is the parameter in the example above.)
* type, --A definition of what kinds of values the parameters can take.
* state, --The set of values of all attributes defining an object.
* source code, --A collection of commands that complies to create an executable program.
* return value, --Output of a method.
* compiler --Something that translates the source code into something the computer can read.

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
-- Additional primitive types in Java include byte (which is a byte-sized integer, or 8-bit), short (which is a short integer, or 16-bit), long (which is a long integer, or 64-bit), float (a single-precision floating point), double (a double-precision floating point), char (a single character), and boolean (a boolean value; true or false).

## What are the types of the following values?

* 0 --int, float(?), double
* "hello" --String
* 101 --int, double, float(?)
* -1 --int, double, float(?)
* true --boolean
* "33" --String
* 3.1415 --double, float(?)

## What would you have to do to add a new field, for example one called name, to a circle object?
-- I would go to the code under "public class Circle" and add "private String name", like so:
---
private String name;
---

## Write the header for a method named send that has one parameter of type String, and does not return a value. 
---
public void send(String message1)
---

## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
---
public Int getNumber(Int number1, int number2)
---

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
-- I think that the book is an object of class Textbook, as objects are specific instances of a class.

## Can an object have several different classes? Discuss.
-- Yes, because the same descriptor can describe several different things (for example, "color" can help identify the color of a circle, a car, or a computer).
