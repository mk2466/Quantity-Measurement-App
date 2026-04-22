# Quantity Measurement App - UC2 (Feet and Inches Equality)

## Description
This application extends UC1 by supporting equality checks for both Feet and Inches measurements.  
Each unit is handled independently, and comparisons are performed only within the same unit type.

## Features
- Equality check for Feet values
- Equality check for Inches values
- Handles null and type safety
- Uses Double.compare for accurate floating-point comparison
- Separate methods for Feet and Inches comparison

## Class Structure
- QuantityMeasurementApp
  - Inner class: Feet
  - Inner class: Inches

## How It Works
1. Two numeric values are passed for comparison
2. Objects of Feet or Inches are created
3. equals() method is used to compare values
4. Returns true if equal, otherwise false

## Example
Input:
1.0 ft and 1.0 ft  
1.0 inch and 1.0 inch  

Output:
Equal (true)  
Equal (true)

## Concepts Covered
- Object equality (equals method)
- Floating-point comparison
- Encapsulation and immutability
- Null safety and type checking
- Code reuse using methods

## Test Cases
- Same value comparison
- Different value comparison
- Null comparison
- Same reference check
- Non-numeric comparison

## Limitations
- Feet and Inches are handled as separate classes
- Code duplication exists between both classes
- Does not support cross-unit comparison (e.g., feet to inches)

## Future Improvement
- Introduce a generic Quantity class
- Support unit conversion (feet ↔ inches)
- Reduce code duplication (DRY principle)

## Requirements
- Java 8 or above

## How to Run
1. Compile:
   javac QuantityMeasurementApp.java

2. Run:
   java QuantityMeasurementApp
