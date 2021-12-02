# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_inv(a), we can find the inverse of the given matrix.
### Step 4: 
Print the values
## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: Jegathish s
#RegisterNumber: 21005410
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
values=np.linalg.inv(a)
print(values)
~~~
## Output:
![output](inverse.jpg)
## Result:
Thus the inverse of given matrix is successfully solved using python program

