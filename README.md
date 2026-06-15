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
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program
## Program:
```

import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
e_va,e_ve=np.linalg.eig(A)
print(f"Eigen values are {e_va} and Eigen Vectors are {e_ve}")
```

## Output:
<img width="1343" height="909" alt="image" src="https://github.com/user-attachments/assets/2c0859ff-00f8-4cdc-8b84-83f59c28e6ed" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
