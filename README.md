# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'
3. Define a package as "from scipy.linalg import lu_factor lu_solve" and create the
variable as "x" include the package in that variable.
4. print the variable 'X'

## Program:
```python
Program to find the eigen values and eigen vectors.
Developed by: Harisha.S
RegisterNumber:24900903    
import numpy as np
a=np.array([[4,2],[2,4]])
eigenvalues,eigenvectors=np.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:
![m4](https://github.com/user-attachments/assets/7f8b2c69-4c5d-4421-b74f-ae6cb650b08e)
## Result:
python program finded the eigenvalues and eigen vectors

Thus the Eigenvalue and Eigenvector is successfully solved using python program
