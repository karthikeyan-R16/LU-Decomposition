# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy
2. Import scipy.linalg
3. Get the matrix as input
4. Calculate the L and U matrix 

## Program:
(i) To find the L and U matrix
```py
Program to find the L and U matrix.
Developed by: karthikeyan  R
RegisterNumber:212222240045

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```py

Program to find the LU Decomposition of a matrix.
Developed by: karthikeyan R
RegisterNumber: 212222240045

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```

## Output :
(i) To find the L and U matrix

![image](https://github.com/karthikeyan-R16/LU-Decomposition/assets/119421232/9a8b0eb0-1901-432f-9976-1ea882909efe)

(ii) To find the LU Decomposition of a matrix

![image](https://github.com/karthikeyan-R16/LU-Decomposition/assets/119421232/f65bbfa6-7f10-4a64-b3e4-523f7f2628fc)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

