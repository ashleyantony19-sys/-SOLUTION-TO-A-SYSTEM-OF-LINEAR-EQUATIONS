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
import numpy as np

A = np.array([[2, 3],
              [1, -2]])

B = np.array([8, -3])

X = np.linalg.solve(A, B)

print("Solution of the system of equations is:")
print("x =", X[0])
print("y =", X[1])
```
## Output:




<img width="911" height="570" alt="image" src="https://github.com/user-attachments/assets/e6d5ef29-6b0f-471f-b11b-4e3bae037d3c" />








<img width="1568" height="347" alt="image" src="https://github.com/user-attachments/assets/c1cab74b-f963-4353-855a-84f3a0454f96" />






## Result: 




Thus the solutions for the linear equations are successfully solved using python program

