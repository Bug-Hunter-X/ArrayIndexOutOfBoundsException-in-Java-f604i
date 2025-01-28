# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`.  The `Bug.java` file contains code that throws this exception. The `BugSolution.java` file shows how to fix it.

The error occurs when the program attempts to access an array element using an index that is not within the valid range of indices for that array.  Java arrays are zero-indexed, meaning the first element is at index 0, the second at index 1, and so on.  Attempting to access an element using a negative index or an index greater than or equal to the array's length will result in an `ArrayIndexOutOfBoundsException`.

To avoid this exception, always ensure that the index you are using to access an array element is within the valid range: 0 to array.length - 1.  Use input validation and boundary checks to prevent out-of-bounds accesses.