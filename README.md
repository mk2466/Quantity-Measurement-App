# Quantity Measurement App - UC1 (Feet Equality)

## Description
This application checks the equality of two numerical values measured in feet. It uses object-oriented principles and ensures proper comparison of floating-point values.

## Features
- Compares two feet measurements
- Handles null and type safety
- Uses Double.compare for precision
- Implements value-based equality

## Class Structure
- QuantityMeasurementApp
  - Inner class: Feet

## How It Works
1. Create two Feet objects with numeric values
2. Call equals() method to compare them
3. Returns true if values are equal, otherwise false

## Example
Input:
1.0 ft and 1.0 ft

Output:
Equal (true)

## Concepts Covered
- Object equality (equals method)
- Floating-point comparison
- Encapsulation and immutability
- Null and type safety

## Test Cases
- Same value comparison
- Different value comparison
- Null comparison
- Same reference check
- Non-numeric comparison

## Requirements
- Java 8 or above
- JUnit 5 for testing

## How to Run
1. Compile:
   javac QuantityMeasurementApp.java

2. Run:
   java QuantityMeasurementApp

## How to Run Tests
Use any IDE or build tool like Maven/Gradle to run JUnit tests
