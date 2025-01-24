# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, providing a string value instead of a number will cause an error.

## Bug
The bug lies in the incorrect usage of the `$inc` operator.  The code attempts to increment the `count` field by the string value '1' which is not allowed.

## Solution
The solution is to provide a numerical value to the `$inc` operator.  The corrected code increments `count` by the number 1.
