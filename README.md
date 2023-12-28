# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
/*
Program to find the L and U matrix.
Developed by: n.bharath
RegisterNumber:23003413 
*/
```
import numpy as np
from scipy.linalg import lu
A=eval (input())
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
/*
Program to find the LU Decomposition of a matrix.
Developed by: N.bharath
RegisterNumber:23003413 
*/
```
import numpy as np
from scipy.linalg import lu,solve
A=eval(input())
B=eval(input())
P,L,U=lu(A)
x=solve(A,B)
print(x)

```

## Output:
![output](![Screenshot 2023-12-28 094505](https://github.com/BHARATHNATRAJAN/LU-Decomposition/assets/147473529/ebea9941-ebcc-401f-8f72-c864d23f8cd3)
)
![output](![Screenshot 2023-12-28 094508](https://github.com/BHARATHNATRAJAN/LU-Decomposition/assets/147473529/08471c6c-63fe-492a-9fdc-4f1ce0b76bb2)
)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

