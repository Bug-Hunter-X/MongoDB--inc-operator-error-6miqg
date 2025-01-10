# MongoDB $inc operator error

This repository demonstrates an example of incorrect usage of the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value. However, using a string value with it results in unexpected behavior and potential data corruption.

## Bug
The bug lies in using a string value ("1") instead of a number (1) with the `$inc` operator. This leads to the update failing or producing unexpected results. 

## Solution
The correct usage is to provide a numerical value to the `$inc` operator to ensure proper incrementing. The solution demonstrates the corrected usage with a numeric value.
