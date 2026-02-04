# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()

### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: PERARASU K 25004665
#RegisterNumber: 212225100034


import numpy as np
matrix = np.array([[6, 2, 3], [3, 1, 1],[10, 3, 4]])
rank = np.linalg.inv(matrix)
print(rank)
```
## Output:
![OUTPUT OF EXP](<Screenshot 2026-02-04 080023.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

