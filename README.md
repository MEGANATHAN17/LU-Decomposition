# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: MEGANATHAN R
RegisterNumber: 24900553
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: MEGANATHAN R 
RegisterNumber: 24900553
'''
import numpy as np
from scipy.linalg import lu,lu_solve,lu_factor
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2024-12-08 134824](https://github.com/user-attachments/assets/610fb8bc-3d02-43b1-a4db-37afd424c088)

![Screenshot 2024-12-08 134838](https://github.com/user-attachments/assets/9e42f511-e5d4-4c76-aa85-fa11632a5c2f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

