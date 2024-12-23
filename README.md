# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The error occurs because the loop condition is incorrect, leading to an attempt to access an array element outside its bounds, resulting in an `IndexOutOfBoundsException`.

## Bug Description
The `Bug.java` file contains a program that initializes an integer array and then iterates over it using a `for` loop.  The loop condition `i <= arr.length` is incorrect; it should be `i < arr.length`. This causes the loop to try accessing an index that doesn't exist in the array.

## Solution
The `BugSolution.java` file provides the corrected code, demonstrating how to correctly iterate over an array using a `for` loop with the condition `i < arr.length`. This ensures that the loop only accesses valid indices within the array.
