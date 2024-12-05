# MongoDB $inc Operator Used on String Field

This example demonstrates an uncommon error in MongoDB: using the `$inc` operator on a string field. The `$inc` operator is designed to increment numeric values; attempting to use it on a string will not produce the expected result and can lead to unexpected behavior or errors.

The `bug.js` file contains code that incorrectly uses `$inc` on a string field. The `bugSolution.js` file provides the corrected implementation.  This example is useful for understanding the limitations and appropriate usage of the MongoDB `$inc` operator.
