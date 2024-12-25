Simple Java Calculator

This repository contains a basic calculator application written in Java. The project demonstrates fundamental programming concepts, including object-oriented programming (OOP), exception handling, and user input via the console.

Features

Addition, Subtraction, Multiplication, Division: Perform basic arithmetic operations.

Error Handling: Prevents division by zero with an appropriate error message.

Interactive Console Application: Users can input numbers and select operations interactively.

Project Structure

Calculator Class: Implements the core functionality for arithmetic operations (addition, subtraction, multiplication, division).

TestCalculator Class: Serves as the entry point for the application. Provides a console-based interface to interact with the calculator.

Prerequisites

Java Development Kit (JDK) version 17 or later.

Basic knowledge of Java to understand or modify the code if needed.

Getting Started

Clone the Repository

git clone https://github.com/your-username/java-calculator.git
cd java-calculator

Compile and Run the Application

Compile the Java code:

javac -d out src/com/example/calculator/*.java

Run the application:

java -cp out com.example.calculator.TestCalculator

How to Use

Launch the application in the terminal.

Enter two numbers when prompted.

Choose an operation from the menu (Add, Subtract, Multiply, Divide).

View the result of the operation.

Example Run

Welcome to the Calculator!
Enter first number: 10
Enter second number: 5
Choose an operation:
1. Add
2. Subtract
3. Multiply
4. Divide
3
Result: 50.0

Customization

Feel free to extend the functionality by adding more operations, such as modulus or power calculations. Modify the Calculator class to include new methods and update the TestCalculator class to handle additional menu options.
