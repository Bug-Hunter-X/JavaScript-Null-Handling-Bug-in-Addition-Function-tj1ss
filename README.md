# JavaScript Null Handling Bug

This repository demonstrates a common, yet subtle, bug in JavaScript related to handling null values in functions. The `foo` function is intended to add two numbers, but it has unexpected behavior when one or both inputs are null.

## Bug Description

The original `bug.js` file contains a function that attempts to add two numbers.  However, it does not correctly handle cases where one or both input parameters are null.  This leads to unexpected null returns instead of handling the nulls appropriately (e.g., by treating them as 0). 

## Solution

The `bugSolution.js` file provides a corrected version of the function that explicitly checks for and handles null values, making the function more robust and reliable.

## How to Run

1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run the code to see the difference in behavior between the original and corrected versions.