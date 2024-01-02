# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import libraries
2.get the matrix from the user
3.find L and U
4.print the solution
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:harish 
RegisterNumber:23013571
 import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:harish 
RegisterNumber:23013571 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```
## Output:
![image](https://github.com/Harishragaventhira/LU-Decomposition/assets/145548269/9971f097-1bc1-4b01-b148-978ca4ffe91d)
![image](https://github.com/Harishragaventhira/LU-Decomposition/assets/145548269/ac64371f-075a-4b49-8d14-bca07b1aa732)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

