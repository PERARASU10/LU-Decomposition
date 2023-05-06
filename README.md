# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy package as np
2.From scipy package import lu
3.Get input from the user
4.Print result

## Program:
(i) To find the L and U matrix
```
'''
Program to find L and U matrix using LU decomposition.
Developed by: PERARASU M
RegisterNumber: 212222100033
'''

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)


```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: PERARASU M
RegisterNumber: 212222100033
'''


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
i)

![m1](https://user-images.githubusercontent.com/118348589/236611490-3ee4d99d-5ddb-49fc-ba8a-df5842d1307d.png)

ii)

![m2](https://user-images.githubusercontent.com/118348589/236611507-457c7474-fe3b-4770-b763-b1d1dc9b9ecd.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

