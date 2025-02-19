# MongoDB $inc Operator Error
This repository demonstrates a common error encountered when using the `$inc` operator in MongoDB update operations. The error arises from providing a string value instead of a numerical value to the `$inc` operator, which results in unexpected behavior or errors.

## Problem
The original code attempts to increment the `count` field by 1, but it uses a string value "1" instead of the numerical value 1. This will result in the update operation failing or producing an incorrect result.

## Solution
The corrected code uses the numerical value 1 to increment the `count` field, ensuring the correct update operation.