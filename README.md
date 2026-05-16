# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy library.
### Step 2: Assign the given matrix using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the Program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: KIRIT LULLA
#RegisterNumber: 212225230139
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="861" height="166" alt="image" src="https://github.com/user-attachments/assets/79b9bc74-99a7-48b9-9b9d-2e3a0d611e1d" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
