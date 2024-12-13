# Julia Function Bug

This repository demonstrates a bug in a simple Julia function. The function is intended to square positive numbers and return zero for non-positive numbers. However, it exhibits unexpected behavior when dealing with zero as input.

## Bug Description
The function `my_function` does not correctly handle the case where the input `x` is zero.  It returns 0, which is expected.  However, the way it handles this case might be unexpected or inefficient compared to other solutions.

## Bug Reproduction
1. Clone this repository.
2. Run `bug.jl`.
3. Observe that for input 0, it returns 0 which might be considered correct or incorrect behavior depending on how you define the behavior for zero.

## Solution
The solution provided in `bugSolution.jl` addresses the issue and provides a clear, concise alternative.
