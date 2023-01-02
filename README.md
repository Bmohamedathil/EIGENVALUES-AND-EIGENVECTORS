# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import numpy as np
### Step 2: 
Assign in np.array() in eigen values and eigen vectors of matrix
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the value and end of the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Mohamed Athil
#RegisterNumber:22008533
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```
## Output:
!['output'](/Screenshot%20from%202023-01-02%2011-55-16.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
