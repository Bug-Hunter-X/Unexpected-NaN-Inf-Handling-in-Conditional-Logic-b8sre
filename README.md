# Julia Bug: Unexpected NaN/Inf Handling in Conditional Logic

This repository demonstrates a common issue in Julia code involving unexpected behavior when handling NaN (Not a Number) and Inf (Infinity) values within conditional statements.

The `bug.jl` file contains a simple function that demonstrates this unexpected behavior. The `bugSolution.jl` file provides a corrected version that addresses the NaN and Inf handling problem.

The problem arises because standard numerical comparisons (>, <, ==) do not always behave intuitively when dealing with NaN and Inf.  This can lead to incorrect program logic if these special values are not properly accounted for.  This is a subtle but frequent issue that can be hard to debug.