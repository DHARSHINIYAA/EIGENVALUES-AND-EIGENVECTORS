# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: create a matrix using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: get the output and end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: DHARSHINIYAA KS
#RegisterNumber:23014039
import numpy as np
a=[[2,2],[1,3]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![Annotation 2023-12-25 224302](https://github.com/DHARSHINIYAA/EIGENVALUES-AND-EIGENVECTORS/assets/149560172/e84323d5-0692-4953-b37f-735eeef30bd2)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
