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
Prepare the list from the given matrix and assign in np.array(). 
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End program. 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Divya R V
#RegisterNumber:23014030
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))


## Output:

![Alt text](<Screenshot 2023-12-13 212655.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
