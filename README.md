# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Harshini Y
RegisterNumber: 212223240050
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: HARSHINI Y
RegisterNumber: 212223240050
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
*/
```

## Output:
![lu decomposition]()
![Screenshot 2024-04-16 213049](https://github.com/harshiniyu/LU-Decomposition/assets/144979786/54d30bff-7462-474a-852b-b68dd3fa0009)

![Screenshot 2024-04-16 213103](https://github.com/harshiniyu/LU-Decomposition/assets/144979786/64f143e5-3c64-48e9-b05f-c49b54c9de0a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

