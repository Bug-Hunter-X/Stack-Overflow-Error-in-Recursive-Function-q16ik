# Stack Overflow Bug in JavaScript

This repository demonstrates a common error in JavaScript: a stack overflow error caused by an incorrectly defined base case in a recursive function. The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected version.

## Bug Description

The recursive function `foo` does not correctly handle the base case where both input arguments `a` and `b` are 0. This leads to infinite recursion, eventually resulting in a stack overflow error.

## Solution

The solution involves adding a check to explicitly handle the base case where `a` and `b` are both 0, ensuring the function terminates and avoids infinite recursion.