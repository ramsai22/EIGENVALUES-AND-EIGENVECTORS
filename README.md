# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in functions for caluculation.

### Step 2: 
Get the input matrix from the user.

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: paida ram sai
#RegisterNumber: 23007931
import numpy as np
a=[[4,2],[2,4]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![Screenshot 2023-11-20 210255](https://github.com/ramsai22/EIGENVALUES-AND-EIGENVECTORS/assets/150319855/893f768b-aad3-4e71-b5d6-9ac73de76e5a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
