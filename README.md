# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the Required Library
### Step 2: Define the Matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the Result

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PUGAZHALENTHI V
#RegisterNumber: 212224100047
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
![image](https://github.com/user-attachments/assets/306062b7-1bbc-47fd-a028-05e7fe3f2912)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
