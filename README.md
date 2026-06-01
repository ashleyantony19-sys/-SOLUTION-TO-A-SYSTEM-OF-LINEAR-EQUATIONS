# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: ASHLEY ANTONY
#RegisterNumber: 212225220013
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
MatrixA=np.array([[1,-3],[3,1]])
const=np.array([0,10])
res=np.linalg.solve(MatrixA,const)
print(res)
```
## Output:

<img width="661" height="220" alt="WhatsApp Image 2026-06-01 at 9 32 18 AM" src="https://github.com/user-attachments/assets/bc1c2a3e-979c-426d-96a0-ec38e3cc2871" />



## Result: 


Thus the solutions for the linear equations are successfully solved using python program

