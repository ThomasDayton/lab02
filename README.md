# Lab 02 -- Chapter 01

## Define the followint terms:
* object, --An Object is an instance of a class.
* class, --A class is a group of objects that describes the kind of object.
* instance, --A specific object that is part of a particular class.
* method, --Operations that can be used to manipulate an object.
* signature, --The name of a method and the parameter types found in its header.
* parameter, --Additional values that some methods require.
* type, --A definition of what kinds of values the parameters can take.
* state, --The set of values of all attributes defining an object.
* source code, --Text that defines the details of a class.
* return value, --A result value that is sent by certain types of code after said code is run.
* compiler --Something that translates code into something the computer can read.

## In Chapter 1 we have mentioned the data types int and String. Java has more predefined data types. Find out what they are and what they are used for. To do this, you can check Appendix B, or look it up in another Java book or in an online Java language manual. One such manual is at [http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html](http://download.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
-- Additional primitive types in Java include byte (which is a byte-sized integer, or 8-bit), short (which is a short integer, or 16-bit), long (which is a long integer, or 64-bit), float (a single-precision floating point), double (a double-precision floating point), char (a single character), and boolean (a boolean value; true or false).

## What are the types of the following values?

* 0 --Int
* "hello" --String
* 101 --Int
* -1 --Int
* true --String
* "33" --Int
* 3.1415 --Int

## What would you have to do to add a new field, for example one called name, to a circle object?
-- I would go to the code under "public class Circle" and add "private string name".

## Write the header for a method named send that has one parameter of type String, and does not return a value. 
-- void send(String message1)

## Write the header for a method named average that has two parameters, both of type int, and returns an int value.
-- Int getNumber(Int number1, int number2)

## Look at the book you are reading right now. Is it an object or a class? If it is a class, name some objects. If it is an object, name its class.
-- I think that the book is an object of class Textbook, as objects are specific instances of a class.

## Can an object have several different classes? Discuss.
-- Yes, because the same descriptor can describe several different things (for example, "color" can help identify the color of a circle, a car, or a computer).
