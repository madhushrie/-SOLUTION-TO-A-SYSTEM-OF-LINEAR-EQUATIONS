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
a=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
b=np.array([-9,4,-1])
c=np.linalg.solve(a,b)
print(c)
```

## Output:
![Screenshot (93)](https://github.com/user-attachments/assets/f506054f-0dd2-43d0-8df8-98400d7c9095)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

