# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: dharshansri
RegisterNumber:212225230055
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
Developed by:dharshansri 
RegisterNumber:212225230055
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
*/
```

## Output:
![lu decomposition]()
<img width="1203" height="784" alt="Screenshot 2026-02-07 082315" src="https://github.com/user-attachments/assets/1b2aacf0-0183-4d1a-b56c-bc952adf5fce" />
<img width="1246" height="603" alt="Screenshot 2026-02-07 082329" src="https://github.com/user-attachments/assets/8753cf7b-3a86-42cf-818f-2b8b83f57184" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

