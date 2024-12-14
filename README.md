# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
 Import numpy module to use the built-in-function for calculation
### Step 2: 
 Prepare the lists from each linear equations and assign in np.array
### Step 3: 
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
 End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Bharath K
#RegisterNumber:24900579
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
e_values,e_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors))

```
## Output:
![output](output.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
