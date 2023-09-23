# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy as np.
### Step 2: Assign np.array() in eigen values and eigen Vectors.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print both the values and vectors,then end the program.

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: ARVIND S
#RegisterNumber: 212222240012
```python
import numpy as np
a = np.array([[4,2],[2,4]])
b,c = np.linalg.eig(a)
print("Eigen values are",b,end=" ")
print("and Eigen Vectors are",c)
```
## Output:
![Screenshot 2023-09-23 141308](https://github.com/S-ARVIND01/EIGENVALUES-AND-EIGENVECTORS/assets/118707337/a4f330d0-e7e2-435c-ad92-fb8189da8a89)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
