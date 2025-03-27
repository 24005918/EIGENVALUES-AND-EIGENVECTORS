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
#Program to find the eigen values and eigen vectors.

#Developed by: santhosh v

#RegisterNumber: 212224230252

import numpy as np

matrix = np.array([[2, 2], 
                   [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

## Output:
![{E08A8E06-5107-41A8-85F4-14BA6C81050D}](https://github.com/user-attachments/assets/54c5b754-6f67-4491-bae2-6c9783af9fac)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
