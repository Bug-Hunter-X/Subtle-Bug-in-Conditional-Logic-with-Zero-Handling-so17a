# Subtle Bug in Julia Conditional Logic

This repository demonstrates a subtle bug in a simple Julia function that involves conditional logic and the handling of zero. The bug is related to how the function behaves when the input is zero and returning the same output as for negative inputs.

## Bug Description
The `my_function` function is designed to return the square of a positive number and 0 otherwise. However, it incorrectly returns 0 for both negative and zero inputs.

## Bug Solution
The solution modifies the conditional logic to specifically check if the input is zero, allowing for different handling compared to negative numbers.

## How to Reproduce
1. Clone this repository.
2. Run the `bug.jl` script using the Julia interpreter. Observe the output. 
3. Run the `bugSolution.jl` script to see the corrected behavior. 
