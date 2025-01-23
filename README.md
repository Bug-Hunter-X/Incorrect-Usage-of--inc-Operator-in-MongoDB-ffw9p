# Incorrect Usage of $inc Operator in MongoDB
This example demonstrates an incorrect usage of the $inc operator in MongoDB, leading to potential errors. The $inc operator is used to increment or decrement a numerical value in a document. However, providing a string value instead of a numerical value will cause unexpected behavior or an error.

## Bug
The bug lies in the way the $inc operator is used. The value to be incremented should be a number, but in this case, a string '1' is used.

## Solution
The solution involves replacing the string '1' with the numerical value 1 to correctly increment the field.