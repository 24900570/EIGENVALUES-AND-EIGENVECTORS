# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
 Import the numpy module to use the built-in functions for calculations.
### Step 2:
 Prepare the lists from each equations and assign in np.array()
### Step 3:
 Using the np.linalg.eig(), we get two results (first is eigenvalue and second is
 eigenvector) of the given matrix.
### Step 4:
END OF PROGRAM
## Program:
```
import numpy as np
a=np.array([[2,2],[1,3]])
values,vector=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vector))
```

## Output:
![Screenshot 2024-12-04 140438](https://github.com/user-attachments/assets/7501c7a9-e81f-4174-aadd-615a3d326bc8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
