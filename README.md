# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1:
Import the numpy module to use the built-in functions for calculation

## Step 2:
Prepare the lists from each linear equations and assign in np.array()

## Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

## Step 4:
End the program
## Program:
# Linear Algebra Exp 2
```
Write a program to find the rank for the given matrix 
[[5,-3,-10],[2,2,-3],[-3,-1,5]]
```
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="1048" height="700" alt="image" src="https://github.com/user-attachments/assets/53665822-00db-4a42-a05b-afbfc68f989d" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

