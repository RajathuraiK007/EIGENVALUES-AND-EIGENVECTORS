# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rajathurai K
#RegisterNumber: 212225100036

import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigen_values,eigen_vectors = np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigen_values,eigen_vectors))
```
## Output:

<img width="1324" height="828" alt="Screenshot 2026-03-26 102248" src="https://github.com/user-attachments/assets/3b8c373c-5b1d-4e9b-bbb3-3a1ae79b95b1" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
