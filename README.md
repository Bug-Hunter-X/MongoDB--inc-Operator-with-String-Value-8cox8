# MongoDB $inc Operator with String Value

This repository demonstrates an uncommon error in MongoDB when using the `$inc` operator with a string value instead of a number.  The `$inc` operator is used to increment a numerical field by a specified amount.  Using a string will lead to unexpected or erroneous behavior.

## Bug
The provided `bug.js` file demonstrates the incorrect usage of the `$inc` operator. The intended behavior is to increment the 'count' field by 1, but due to using the string '1', it will either fail or produce unexpected results.

## Solution
The `bugSolution.js` file shows the correct usage of the `$inc` operator using a numerical value, ensuring correct increment behavior.

This example is relevant for anyone working with MongoDB and its update operators to avoid unexpected errors and ensure data integrity.