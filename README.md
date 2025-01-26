# COBOL Array Out-of-Bounds Access Bug

This repository demonstrates a common, yet subtle, error in COBOL programs: accessing an array element beyond its declared bounds. This can lead to unexpected results or program crashes, making it crucial to carefully manage array indices.

## The Bug

The `bug.cob` file contains a COBOL program that attempts to access an array element outside its defined range. The program intends to calculate the sum of numbers from 1 to 100, but due to an off-by-one error, it attempts to access an element that does not exist.

## The Solution

The `bugSolution.cob` file demonstrates how to correct this issue by ensuring that array access remains within the valid index range. This involves proper use of array subscripts and careful consideration of loop boundaries.