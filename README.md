# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs when the loop condition `i <= array.length` is used instead of `i < array.length`. This leads to an attempt to access an element beyond the array's bounds, resulting in an `ArrayIndexOutOfBoundsException`.

The `Bug.java` file contains the buggy code, while `BugSolution.java` provides the corrected version.