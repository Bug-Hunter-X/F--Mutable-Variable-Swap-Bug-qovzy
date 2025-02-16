# F# Mutable Variable Swap Bug

This repository demonstrates a common error in F# when working with mutable variables and attempting to swap their values using a function. The issue arises because F# passes arguments by value, not by reference.  Therefore, the swap function operates on copies of the original variables, leaving the original variables unchanged.

The `bug.fs` file contains the erroneous code, and the `bugSolution.fs` file provides the corrected implementation.
