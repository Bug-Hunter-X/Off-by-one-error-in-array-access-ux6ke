# Off-by-One Error in Array Access

This repository demonstrates a common off-by-one error in Java, where the loop index goes beyond the bounds of an array, resulting in an `ArrayIndexOutOfBoundsException`.

## Bug Description
The `bug.java` file contains Java code that attempts to populate an array with values. The `for` loop uses `i <= arr.length` as its termination condition, leading to an attempt to access an index that is out of bounds.

## Solution
The corrected code, in `bugSolution.java`, modifies the loop condition to `i < arr.length`, ensuring that the loop iterates correctly within the array's boundaries.