# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Start the program.
### Step 2:Import the NumPy library using import numpy as np.
### Step 3:Define the square matrix using np.array() and store it in a variable.
### Step 4:Find the determinant of the matrix using np.linalg.det() to check whether the inverse exists (determinant ≠ 0).
### Step 5:If the determinant is not zero, find the inverse of the matrix using np.linalg.inv().
### Step 6:Store the inverse in a variable and print the result.
### Step 7:Stop the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: HARINI A
#RegisterNumber: 212223040056
import numpy as np
A = np.array([[6, 2, 3],[3, 1, 1],[10, 3, 4]])
det = np.linalg.det(A)
inverse = np.linalg.inv(A)
print(inverse)

```
## Output:
<img width="779" height="784" alt="image" src="https://github.com/user-attachments/assets/ee7fd705-1ea2-4761-950d-f90ebff78583" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

