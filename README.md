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
#Developed by: NARESH.R
#RegisterNumber: 23005559
import numpy as np
A = [[2,2],[1,3]]
Values,Vectors = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(Values,Vectors))
```
## Output:
![Screenshot 2023-12-24 164850](https://github.com/feryjfgkuyfgewjfgew/EIGENVALUES-AND-EIGENVECTORS/assets/150319377/14e9dbac-040a-410f-82e3-4012174248e7)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
