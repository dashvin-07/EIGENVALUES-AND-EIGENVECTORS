# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Start the program.
### Step 2:
Import the numpy library using import numpy as np.
### Step 3:
Define a square matrix (2x2, 3x3, etc.) using np.array().
### Step 4:
Use the function np.linalg.eig(matrix) to compute the eigenvalues and eigenvectors of the matrix.
This function returns two outputs:
The first is an array of eigenvalues.
The second is a 2D array of eigenvectors (each column is an eigenvector).
### Step 5: 
Display the eigenvalues and eigenvectors using the print() function.
### Step 6:
End the program.

## Program:!
#Program to find the eigen values and eigen vectors.
#Developed by: Dashvin
#RegisterNumber:212224100008
```
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:

![image](https://github.com/user-attachments/assets/470aaa76-5ca4-4eba-8511-535a85902d49)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
