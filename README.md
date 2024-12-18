# Unconditional Return in MATLAB Function

This repository demonstrates a common MATLAB error where an unconditional return statement within a conditional block causes a function to terminate prematurely, leading to incomplete execution.

## Problem Description
The issue lies in the `myFunction` function.  Due to the `return;` statement inside the `if` block, the function will always return early if `someCondition` is true. The code after the `if` block will never be executed in such cases.

## Solution
The solution involves removing the unconditional `return;` statement or modifying it to only return under specific conditions to allow the code to execute properly. 
