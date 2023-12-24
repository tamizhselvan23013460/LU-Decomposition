# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Write the code appropriately
3. Check the code
4. Run the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: TAMIZHSELVAN B
RegisterNumber: 23013460
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: TAMIZHSELVAN B
RegisterNumber: 23013460
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array([[3,2,7],[2,3,1],[3,4,1]])
b = np.array([4,5,7])
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)


```

## Output:
![Alt text](<LU Output 1.png>)
![Alt text](<LU Output 2.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

