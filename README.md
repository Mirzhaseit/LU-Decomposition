# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Algorithm
1. Input the Matrix
2. Initialize Matrices L and U
3. Perform Decomposition
4. Output 𝐿 and 𝑈 Matrices

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Mirzha Fathima S
RegisterNumber: 24901261
*/
import numpy as np
from scipy.linalg import lu 
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:  Mirzha Fathima S
RegisterNumber: 24901261
*/

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![lu decomposition]()
![image](https://github.com/user-attachments/assets/9c2dad18-2316-453f-b9c0-c31f67217e2a)
![image](https://github.com/user-attachments/assets/4100c5c9-eb3b-4ac3-a34d-a66c394a4ff8)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

