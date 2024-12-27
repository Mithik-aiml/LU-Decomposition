# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
i)
1. find the 1 and u matirx by using numpy and linalg from scipy

2. print the 1 matrix and u matirx

3. find the lu decomposition by using numpy and lu_factor and lu_solve

4. print the the following  matrix

ii)
1. Get necessary libraries.
2. Get input for coefficient matrix (A) and constant vector (B).
3. Perform LU decomposition on A using lu_factor.
4. Solve the system using lu_solve with the decomposition result (X) and B.
5. Print the solution.
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:G.Mithik jain 
RegisterNumber: 24001881
*/
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: G.Mithik jain
RegisterNumber: 24001881
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
i)
![alt text](<Screenshot 2024-12-26 132549-1.png>)

ii)
![alt text](<Screenshot 2024-12-26 132654.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

