# CSS calc() Function Unexpected Results

This repository demonstrates a common issue with the CSS `calc()` function where unexpected results occur due to operator precedence, type coercion, or unit incompatibility. The `bug.css` file contains the problematic CSS, while `bugSolution.css` offers a solution to resolve the issue.  The problem arises from incorrect usage of the calc() function, leading to miscalculations and layout problems.

## Problem Description

The `calc()` function is powerful but requires careful attention to detail. Inconsistent spacing around operators or combining incompatible units often leads to unexpected behavior.

## Solution

The `bugSolution.css` file showcases how to correctly use the `calc()` function to achieve the desired outcome.  This includes explicit unit usage and ensuring correct order of operations. The solution is generally achieved by careful review of operator precedence, unit consistency and proper spacing. 