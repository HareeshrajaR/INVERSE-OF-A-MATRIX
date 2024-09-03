## DATE:
## EX NO:3 INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array().
### Step 3:
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix.
### Step 4: 
End the program.
## Program:
### Program to find the inverse of a matrix.
### Developed by: HAREESH R
### RegisterNumber:212223230068
```
import numpy as np
matrix = np.array([[2 , 1 ,1], [1, 1, 1], [1, -1, 2]])
B = np.linalg.inv(matrix)
print(B)
```

## Output:
![Screenshot 2024-09-03 085359](https://github.com/user-attachments/assets/d6a2a3da-6993-41ce-85bd-675613421fc1)


## Result:
Thus the inverse of given matrix is successfully solved using python program

