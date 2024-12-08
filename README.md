# Python ZeroDivisionError Bug
This repository demonstrates a common error in Python: a ZeroDivisionError when calculating the average of numbers in a list. The bug occurs when the input list is unexpectedly empty.  The solution shows how to gracefully handle this case.

## Bug
The `calculate_average` function in `bug.py` does not explicitly handle the case of an empty input list, leading to a `ZeroDivisionError`. 

## Solution
The `bugSolution.py` file contains a corrected `calculate_average` function that checks if the input list is empty before performing calculations, preventing the error.