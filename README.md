# MongoDB $inc Operator with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical field by a specified value.  However, providing a string value instead of a number results in unexpected behavior or errors.

## Bug Description

The provided code attempts to increment the `field` in a document with `_id: 1` by the value '1' (a string).  This leads to an error or unexpected behavior, as `$inc` expects a numeric value.

## Solution

The correct usage of `$inc` requires a numerical value.  The solution demonstrates how to correctly use `$inc` to increment the field by 1.