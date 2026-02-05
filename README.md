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
import numpy as np

A = np.array([[-2,  2, -3],
              [ 2,  1, -6],
              [-1, -2,  0]])

eigen_values, eigen_vectors = np.linalg.eig(A)

print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)

## Output:

<img width="1240" height="155" alt="Screenshot 2026-02-05 135806" src="https://github.com/user-attachments/assets/c94b0564-e2d1-486d-8892-171d370c2390" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
