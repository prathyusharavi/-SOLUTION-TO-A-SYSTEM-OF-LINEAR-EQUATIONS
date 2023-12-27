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
#Developed by:YENUGANTI PRATHYUSHA 
#RegisterNumber:23009045
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
C=np.linalg.solve(A,B)
print(C)
```
## Output: 
![image](https://github.com/prathyusharavi/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/147474424/dc780b9d-4575-47fe-8179-1829233408ae)



## Result:
 thus,the solutions for the linear equations are successfully solved using python program

