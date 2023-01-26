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
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: R.JAYAMANI
#RegisterNumber: 22008124
import numpy as np
a=np.array([[4,2],[2,4]])
res,v=np.linalg.eig(a)
print("Eigen values are",res,"and Eigen Vectors are",v)
```

## Output:
![Eigen value](https://user-images.githubusercontent.com/85949888/214745736-3f71d04b-4341-427b-8ee3-628842241566.png)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
