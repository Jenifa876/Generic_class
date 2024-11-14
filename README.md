# Generic class
# Introduction
This project provides a simple example of Java generics with a generic class, Test<T, U>. This class is designed to hold two objects of potentially different types, making it flexible for various data types and use cases.

The Generic class demonstrates how to use the Test class with specific types (String and Integer).

# Usage
This code is meant to be used for understanding the basic implementation of generics in Java. The class Test can store objects of any two types defined at the time of object creation.

# Features
Generic class to hold two different types.
A method to print the values of stored objects.

# How It Works
The program consists of the following components:

Test<T, U> Class: This is a generic class with two type parameters, T and U.

T obj1: Holds an object of type T.
U obj2: Holds an object of type U.
The constructor Test(T obj1, U obj2) initializes these two objects.
public void print(): Prints the two objects to the console.
Generic Class: Contains the main method where an instance of Test is created with specific types (String and Integer), and then the print() method is called.

# Conclusion
This program serves as an introductory example of Java generics, demonstrating how to create a class that can handle multiple types, defined at runtime. This is especially useful for writing flexible and type-safe code in Java.
