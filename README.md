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
#Developed by: NITHIYANANDAN N
#RegisterNumber:212222230099
import numpy as np
a = np.array([[1,-3],[3,1]])
b = np.array([0,10])
result = np.linalg.solve(a,b)
print(result)
```

## Output:
![image](https://github.com/NITHIYANANDAN278/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/121784636/4de81164-9cce-4569-827e-c190aada5768)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

