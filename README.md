# PHP Unexpected Null Return Value from Function

This repository demonstrates an uncommon bug in PHP: a missing return statement in a function that is implicitly expected to return a value.

The `bug.php` file shows the buggy code, where the `myFunction()` does not have an explicit `return` statement and returns `null` by default.  This can be particularly hard to debug if the developer assumes the function is returning a specific value. 

The `bugSolution.php` file provides the corrected code with the added `return` statement. This ensures that the function returns the expected value.

This bug highlights the importance of explicit coding and thorough testing to avoid unexpected behavior.