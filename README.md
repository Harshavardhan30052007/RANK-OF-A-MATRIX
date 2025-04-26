# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library
This allows us to use mathematical functions like finding the rank of a matrix.
### Step 2: Define the matrix
A 3x3 matrix is created using np.array() with specific integer values.
### Step 3:Calculate the rank
The np.linalg.matrix_rank() function finds the rank of the matrix (i.e., the number of linearly independent rows or columns).
### Step 4: Print the result
The calculated rank is printed to the console.
## Program:
```
#Program to find the rank of a matrix.
#Developed by:Harshavardhan.K.B
#RegisterNumber:212224240054

import numpy as np
a = np.array([[3,2,5],[1,1,2], [3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
![Screenshot 2025-04-26 111043](https://github.com/user-attachments/assets/e3676c07-533a-46ba-ba89-f81fae67041c)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

