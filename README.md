# Constructor-OverloadingAim

## Aim:
To study and implement the concepts of constructor overloading and function overloading in C++.

## Theory:

In Object-Oriented Programming (OOP), polymorphism is an important concept which means “one name, many forms.” In C++, polymorphism is of two types:

Compile-time polymorphism (Static binding): Achieved using function overloading and operator overloading.

Run-time polymorphism (Dynamic binding): Achieved using virtual functions and inheritance.

This experiment focuses on constructor overloading and function overloading, which are both examples of compile-time polymorphism.

### 🔹 Constructor Overloading

A constructor is a special member function that automatically initializes objects of a class when they are created.

Constructor overloading means having more than one constructor in a class, each with different parameter lists.

The compiler decides which constructor to call depending on the arguments passed while creating an object.

Types of constructors generally used are:

Default constructor: Initializes data members with default values.

Parameterized constructor: Initializes objects with user-provided values.

Copy constructor: Creates a new object as a copy of an existing object.

Real-life example: In a Student class, we may create a student without details (default constructor), with only a name (single parameter), or with both name and age (two parameters).

### 🔹 Function Overloading

Function overloading allows multiple functions to have the same name but different parameter lists (different type, number, or order of parameters).

The compiler differentiates these functions at compile time and calls the correct one based on the arguments passed.

This reduces confusion of using multiple names and makes code cleaner.

It is a form of compile-time polymorphism.

Real-life example: A calculator can perform addition of two integers, two floating-point numbers, or three integers. Instead of creating separate functions (addInt(), addFloat()), we can use one function name add() with different parameter lists.

### 🔹 Advantages of Constructor and Function Overloading

Improves readability and reusability of code.

Provides flexibility in object creation and function calling.

Reduces unnecessary function names, making programs more structured.

Demonstrates the power of compile-time polymorphism in C++.

## Algorithm:

Start the program.

Create a class with data members.

Implement constructor overloading:

Define a default constructor.

Define parameterized constructors with different arguments.

Implement function overloading:

Define multiple functions with the same name but different parameter lists.

In the main() function:

Create objects using different constructors.

Call overloaded functions with different sets of arguments.

Display results.

Stop the program.

## Conclusion:

From this experiment, we conclude that:

Constructor Overloading allows objects to be created and initialized in multiple ways using different constructors.

Function Overloading allows a single function name to perform multiple tasks based on the parameters passed.

Both are examples of compile-time polymorphism in C++.

They make programs more flexible, readable, and maintainable, avoiding complexity and improving usability.
