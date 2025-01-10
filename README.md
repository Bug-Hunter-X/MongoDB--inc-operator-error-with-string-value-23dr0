# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field, but providing a non-numeric value will result in an error.

## Bug
The provided code attempts to increment the `field` using the string 'abc'. This is incorrect and will cause an error.

## Solution
The solution involves ensuring that the value provided to the `$inc` operator is a valid number.  The corrected code snippet is provided in `bugSolution.js`.