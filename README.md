# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built in functions for calculation.
### Step 2: 
prepare the lists from each linear equations and assign in np.array().
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the module

## Program:
~~~
#Program to find the eigen values and eigen vectors.
#Developed by:panimalar.p 
#RegisterNumber:22009107
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
~~~
## Output:
![Screenshot (165)](https://user-images.githubusercontent.com/121490826/214615854-5825e811-1ae6-48b3-912d-0868d88aa067.png)
![Screenshot (166)](https://user-images.githubusercontent.com/121490826/214615991-1d310ea2-054c-4cd7-93e5-5d6c7a85293f.png)




## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
