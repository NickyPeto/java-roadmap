# Java Fundamentals

## Overview

Java is a programming language and computing platform first released by Sun Microsystems in 1995. It is a general-purpose, class-based, object-oriented programming language designed to have fewer implementation dependencies. 

Java is known for its speed, security, and reliability, making it a popular choice for a wide range of applications. It is used extensively in various environments including:

- Laptops
- Data centers
- Game consoles
- Scientific supercomputers
- Cell phones

Java's versatility and robustness make it a key technology in application development across diverse platforms.

## Basic syntax

[Code gym's aricle](https://codegym.cc/groups/posts/java-syntax)

When programming in Java, adhere to the following syntax rules:

- **File and Class Naming**:
  - The file name must be identical to the class name.
  - Each class is typically placed in a separate file with a `.java` extension.
  - Class files are organized into folders known as packages.

- **Case Sensitivity**:
  - Java is case-sensitive; for example, `String` is not equal to `string`.

- **Main Method**:
  - Java program execution begins with the `main` method: `public static void main(String[] args)`.
  - The `main()` method is a required component of any Java program.

- **Methods**:
  - A method (also known as a procedure or function) is a sequence of commands defining the behavior of an object.
  - The order of methods in a program file does not affect the execution.

- **Naming Conventions**:
  - Class names should start with an uppercase letter. For multiple words, capitalize the first letter of each word (e.g., `MyFirstJavaClass`).
  - Method names should start with a lowercase letter. For multiple words, use camelCase (e.g., `public void myFirstMethodName()`).

- **File Extensions**:
  - Files should be saved with the class name and a `.java` extension (e.g., `MyFirstJavaClass.java`).

- **Code Blocks and Statements**:
  - Code blocks are enclosed in curly braces `{...}`.
  - Each statement must end with a semicolon (`;`).

## Java Variables and Data Types

In Java, variables are used to store data. Each variable has a data type, name (identifier), and value. 

### Data Types

Data types in Java are categorized into primitive and non-primitive (reference) types:

- **Primitive Data Types**:
  - **Integers**:
    - `byte`: 8-bit integer
    - `short`: 16-bit integer
    - `int`: 32-bit integer
    - `long`: 64-bit integer
  - **Fractionals**:
    - `float`: 32-bit floating-point
    - `double`: 64-bit floating-point
  - **Logical Values**:
    - `boolean`: Represents `true` or `false`
  - **Symbolic Values**:
    - `char`: Represents a single 16-bit Unicode character