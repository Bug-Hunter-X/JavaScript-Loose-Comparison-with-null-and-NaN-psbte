# JavaScript Loose Comparison with null and NaN
This repository demonstrates a common JavaScript error related to loose comparison (==) with null and NaN.  The `bug.js` file contains code with the error, while `bugSolution.js` provides a corrected version.

The issue arises when attempting to check if a variable is null using loose comparison. Loose comparison does not treat NaN as equal to null.  The solution involves using strict comparison (===) and a check for NaN.