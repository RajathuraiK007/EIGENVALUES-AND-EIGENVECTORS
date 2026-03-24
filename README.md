# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Rajathurai K
#RegisterNumber: 25016579

import numpy as np
matrix=np.array([[4,2],[2,4]])
eigen_values,eigen_vectors = np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigen_values,eigen_vectors))
```
## Output:

<img width="1500" height="843" alt="image" src="https://github.com/user-attachments/assets/39d9cbdf-cb80-4a0a-91fa-02bb47a1eeec" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
