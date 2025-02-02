# MongoDB $inc Operator Error with String Value
This repository demonstrates an example of an error caused by incorrectly using the MongoDB $inc operator with a string value instead of a number.

The `bug.js` file contains the incorrect code, while `bugSolution.js` provides the correct implementation.

## Problem
The `$inc` operator is used to increment or decrement numeric values in MongoDB.  Passing a string value to `$inc` will result in an error.

## Solution
Ensure that the value provided to `$inc` is a number.  This can often involve careful type checking before database operations.