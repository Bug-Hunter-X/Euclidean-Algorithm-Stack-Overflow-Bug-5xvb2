# Euclidean Algorithm with Stack Overflow Bug

This repository demonstrates a common error in recursive functions: stack overflow due to inefficient recursion. The provided JavaScript code implements the Euclidean algorithm for finding the greatest common divisor (GCD) of two numbers but fails for certain inputs causing a stack overflow.  A solution is provided in `bugSolution.js`.

**Bug:** The original code (`bug.js`) uses recursion without a proper base case, leading to an infinite number of recursive calls for certain inputs, resulting in a stack overflow error.

**Solution:** The fixed code (`bugSolution.js`) includes an additional check to ensure that the function always makes progress toward termination. This prevents the infinite recursion. 

This example highlights the importance of carefully designing recursive functions to avoid stack overflow errors.