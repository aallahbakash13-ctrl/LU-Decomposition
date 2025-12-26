# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program and import the required libraries, such as numpy or scipy.linalg.
2. Define or read the matrix for which the LU Decomposition needs to be performed.
3. Use the LU decomposition function (such as scipy.linalg.lu()) to obtain
the Lower triangular matrix (L), Upper triangular matrix (U), and permutation matrix P.
4. Print the matrices L, U, and P

## Program:
```
(i) To find the L and U matrix
/*
Program to find the L and U matrix.
Developed by: ALLAHBAKASH A
RegisterNumber: 25004583
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by: ALLAHBAKASH A
RegisterNumber: 25004583
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
```
## Output:
<img width="1293" height="877" alt="Screenshot 2025-12-26 211920" src="https://github.com/user-attachments/assets/9c66ccde-cb60-46b1-8a1e-68de77120a64" />

<img width="1338" height="857" alt="Screenshot 2025-12-26 211902" src="https://github.com/user-attachments/assets/309eab8f-73f5-4ee7-8133-1794c1730120" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

