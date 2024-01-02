# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SREEVALSAN V
#RegisterNumber: 23012962
import numpy
a=[[2,-3,0],[2,-5,0],[0,0,3]]
w,v=numpy.linalg.eig(a)
print("Eigen values are",w,"and Eigen Vectors are",v)
```

## Output:

![Alt text](image.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
