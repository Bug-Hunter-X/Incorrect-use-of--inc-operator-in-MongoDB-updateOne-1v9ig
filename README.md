# Incorrect use of $inc operator in MongoDB

This example demonstrates an incorrect use of the `$inc` operator in a MongoDB `updateOne` operation. The `$inc` operator is used to increment a numerical field by a specified value.  However, using a string value instead of a number leads to unexpected results.

The bug is shown in `bug.js` and the solution is provided in `bugSolution.js`.