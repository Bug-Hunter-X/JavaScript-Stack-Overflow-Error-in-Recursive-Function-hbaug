# JavaScript Stack Overflow Error

This repository demonstrates a common JavaScript error: a stack overflow caused by uncontrolled recursion.  The `bug.js` file contains a function with a flawed recursive implementation. The `bugSolution.js` provides a corrected version.

The issue arises from the absence of a proper base case in the recursive function, leading to infinite calls until the call stack is exhausted.  The solution implements a suitable base case to prevent this.