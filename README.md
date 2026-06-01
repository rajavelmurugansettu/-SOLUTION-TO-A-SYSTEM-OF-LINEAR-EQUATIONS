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
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B = np.array([-9,4,-1])
le = np.linalg.solve(A,B)
print(le)

## Output:
<img width="1346" height="343" alt="Screenshot 2026-06-01 134809" src="https://github.com/user-attachments/assets/dc4b6f45-f92f-4512-9329-e8198a68622a" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

