# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Form a matrix
### Step 2: 
Give the values
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Run the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Jayasree R
#RegisterNumber:23009250
import numpy as np
A=[2,-3,0],[2,-5,0],[0,0,3]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

```
## Output:
![Alt text](<Eigen values and Eigen vectors.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
