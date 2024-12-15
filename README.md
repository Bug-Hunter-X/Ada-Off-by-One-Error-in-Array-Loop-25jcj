# Ada Off-by-One Error Example
This example demonstrates a common off-by-one error in Ada when iterating over an array.  The provided code attempts to access elements beyond the defined bounds of the array, resulting in a runtime exception.

The `bug.ada` file contains the erroneous code. The `bugSolution.ada` file provides the corrected version.

This is a classic example of a subtle error that can be difficult to identify, especially in larger codebases. This example highlights the importance of careful array index management in Ada.