# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step1:
from scipy.linalg import lu: This imports the LU decomposition function from the SciPy linear algebra module.
import numpy as np: Imports NumPy and assigns it the alias np.
## step2:
arr = eval(input()): This takes user input, which is expected to be a list representing a matrix.
A = np.array(arr): Converts the input (assumed to be a matrix) into a NumPy array.
## step3:
P, L, U = lu(A): Performs LU decomposition on the matrix A using the LU function from SciPy.
P: Permutation matrix
L: Lower triangular matrix
U: Upper triangular matrix
## step4:
print(L): Prints the lower triangular matrix obtained from the LU decomposition.
print(U): Prints the upper triangular matrix obtained from the LU decomposition.

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Thamizh kumaran S
RegisterNumber: 23004070
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Thamizh kumaran S
RegisterNumber: 23004070
'''
# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print (solution)    
*/
```

## Output:
![lu decomposition](https://github.com/Thamizhjo/LU-Decomposition/assets/123891476/a286612a-f94d-431a-b553-b05cfba37be7)
![lu decomposition](https://github.com/Thamizhjo/LU-Decomposition/assets/123891476/f0b78b66-5865-40d9-94ab-c5a8cbe28ed2)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

