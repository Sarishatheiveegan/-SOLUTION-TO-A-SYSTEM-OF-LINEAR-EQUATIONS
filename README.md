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
#Developed by: Marino Sarisha T
#RegisterNumber:212223240084
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
result=np.linalg.solve(A,B)
print(result)
```
## Output:
![Screenshot 2024-03-24 110643](https://github.com/Sarishatheiveegan/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/144979465/7584d5b5-2766-453a-aa5c-79d0bc3b277a)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

