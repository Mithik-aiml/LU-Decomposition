# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### step1:
     Import numpy as np.
### step2:
     Import lu from scipy.linalg.
### step3:
     Declare the array as A.
### step4:
     Assign P,L,U (Pivot matrix,L matrix and U matrix) to lu of A.
### step5:
     print L and U

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

![alt text](<Screenshot 2024-12-16 073710.png>)

![alt text](<Screenshot 2024-12-16 073726.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

