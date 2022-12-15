# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS

## Aim:

To write a python program to find a solution to a system of linear equations.

## Equipment’s required:

1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step 1: Import numpy package
### Step 2: Get the import matrix
### Step 3: Find the system of linear equation
### Step 4: Print the result

## Program:
```python
#Program to find the solution for the given linear equations.
#Developed by: Prajeeth K T
#RegisterNumber: 22002267
import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5,-3])
saamy=np.linalg.solve(A,B)
print(saamy)
```

## Output:
![](./System%20of%20linear%20equation.png) 

## Result: 

Thus the solutions for the linear equations are successfully solved using python program