# Quantity Measurement App - UC3 (Generic Quantity Class)

## Description
This application refactors Feet and Inches into a single generic Quantity class using the DRY principle. It supports comparison across different units by converting values into a common base unit (feet).

## Features
- Single Quantity class for all length units
- Supports Feet and Inches
- Cross-unit comparison (1 ft = 12 inches)
- Eliminates duplicate code
- Uses enum for unit safety

## Class Structure
- QuantityMeasurementApp
  - enum: LengthUnit
  - class: Quantity

## How It Works
1. Create Quantity objects with value and unit
2. Convert values into base unit (feet)
3. Compare using equals()

## Example
Input:
Quantity(1.0, FEET) and Quantity(12.0, INCH)

Output:
Equal (true)

## Concepts Covered
- DRY Principle
- Enum usage
- Object equality
- Floating-point comparison
- Encapsulation
- Abstraction

## Test Cases
- Feet to Feet equality
- Inch to Inch equality
- Feet to Inch conversion equality
- Inch to Feet conversion equality
- Different values
- Null handling
- Same reference
- Invalid unit handling

## Advantages
- No code duplication
- Easy to add new units
- Centralized conversion logic

## Requirements
- Java 8 or above

## How to Run
1. Compile:
   javac QuantityMeasurementApp.java

2. Run:
   java QuantityMeasurementApp
