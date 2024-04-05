# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: 
End the program
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: HEMAVATHY.S
#RegisterNumber: 212223230076
import numpy as np

# Define the matrix
matrix = np.array([[2, 1, 1],
                   [1, 1, 1],
                   [1, -1, 2]])

# Find the inverse of the matrix
inverse_matrix = np.linalg.inv(matrix)

print(inverse_matrix)
```
## Output:
![maths3](https://github.com/Hemaatchu/INVERSE-OF-A-MATRIX/assets/147328300/0c49dddf-8d22-4306-ab94-262c0b9f2add)

## Result:
Thus the inverse of given matrix is successfully solved using python program

