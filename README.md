# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: vishwa v
#RegisterNumber:212224110062
import numpy as np
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
e_values,e_vectors=np.linalg.eig(matrix)
print(f"Eigen values are {e_values} and Eigen Vectors are {e_vectors}")
```
## Output:
![](<Screenshot 2025-05-06 152905.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
