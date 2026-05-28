# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1: Import the numpy module to use the built-in functions for calculation

Step 2: Prepare the lists from each linear equations and assign in np.array()

Step 3: Using the np.linalg.inv(), we can find the solutions.

Step 4: End the program
## Program:
```
#Program to find the eigen values and eigen vectors.  
#Developed by: G.Sushanth  
#RegisterNumber:212225230088  
import numpy as np  
a=np.array([[4,2],[2,4]])  
values,vectors=np.linalg.eig(a)  
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")  
```

## Output:
<img width="1208" height="786" alt="{1005B0BB-D611-4056-8589-F1AAB66A1D14}" src="https://github.com/user-attachments/assets/fe5a2d23-ce1d-4b90-8b39-8ab96b1b235e" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
