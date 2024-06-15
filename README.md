# DCIT 318: Programming II - Assignment 2 - 10945445

This repository contains three C# console applications demonstrating different aspects of object-oriented programming (OOP) in C#. Each application focuses on a specific OOP concept: inheritance and method overriding, abstract classes and methods, and interfaces.

## Applications

### 1. Inheritance and Method Overriding
**Description**: Demonstrates the use of inheritance and method overriding in C#.

**Classes**:
- **Animal**: A base class with a virtual method `MakeSound()`.
- **Dog**: A derived class that overrides `MakeSound()` to print "Bark".
- **Cat**: A derived class that overrides `MakeSound()` to print "Meow".

**Usage**: Instances of `Animal`, `Dog`, and `Cat` are created, and their `MakeSound()` methods are called.

### 2. Abstract Classes and Methods
**Description**: Illustrates the use of abstract classes and methods in C#.

**Classes**:
- **Shape**: An abstract class with an abstract method `GetArea()`.
- **Circle**: A derived class that implements `GetArea()` to calculate the area of a circle.
- **Rectangle**: A derived class that implements `GetArea()` to calculate the area of a rectangle.

**Usage**: Instances of `Circle` and `Rectangle` are created, and their areas are displayed.

### 3. Interfaces
**Description**: Shows the implementation of interfaces in C#.

**Interfaces**:
- **IMovable**: An interface with a method `Move()`.

**Classes**:
- **Car**: A class that implements `IMovable` and prints "Car is moving" when `Move()` is called.
- **Bicycle**: A class that implements `IMovable` and prints "Bicycle is moving" when `Move()` is called.

**Usage**: Instances of `Car` and `Bicycle` are created, and their `Move()` methods are called.

## Repository Structure
- **InheritanceDemo/**: Contains the code for the inheritance and method overriding task.
- **AbstractClassDemo/**: Contains the code for the abstract classes and methods task.
- **InterfaceDemo/**: Contains the code for the interfaces task.
