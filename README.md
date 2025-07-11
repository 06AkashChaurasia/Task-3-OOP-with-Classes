# Task-3-OOP-with-Classes
Create a Java program demonstrating classes, inheritance, and method overriding
# Java OOP Demo: Classes, Inheritance, and Method Overriding

This project demonstrates basic Object-Oriented Programming (OOP) concepts in Java:
- **Classes**
- **Inheritance**
- **Method Overriding**

## Files

- `OOPDemo.java` — Contains all the classes (`Animal`, `Dog`) and the `main` method.

## How it Works

1. **Base Class: `Animal`**
   - Has a method `makeSound()` which prints `"Animal makes a sound"`.

2. **Derived Class: `Dog`**
   - Inherits from `Animal` using `extends`.
   - Overrides the `makeSound()` method to print `"Dog barks"`.

3. **Main Method**
   - Creates an `Animal` object → calls `Animal` version of `makeSound()`.
   - Creates a `Dog` object with an `Animal` reference → calls `Dog` version of `makeSound()` due to **dynamic method dispatch**.

## Example Output


