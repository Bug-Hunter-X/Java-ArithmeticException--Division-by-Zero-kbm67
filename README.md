# Java ArithmeticException: Division by Zero

This repository demonstrates an uncommon Java runtime exception: `ArithmeticException`.  Specifically, it shows what happens when an integer division attempts to divide by zero. This is a classic error but can manifest subtly in larger codebases. The solution adds a check to handle potential division by zero.

## Bug
The `UncommonBug.java` file contains the problematic code.  The main method attempts to divide an integer by zero.  This leads to an `ArithmeticException` at runtime.

## Solution
The `UncommonBugSolution.java` file provides a corrected version with a conditional statement to prevent the division by zero. This demonstrates good defensive programming practice.