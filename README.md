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
Developed by: MANOJ.R
RegisterNumber: 24900222 
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
Amatrix=np.array(eval(input()),dtype='i')
Bmatrix=np.array(eval(input()),dtype='i')
Xmatrix=lu_factor(Amatrix)
solution=lu_solve(Xmatrix,Bmatrix)
print(solution)
```

## Output:
![Screenshot 2024-12-15 211017](https://github.com/user-attachments/assets/69e1a674-a451-4717-8947-9c5dfb6166ac)
![Screenshot 2024-12-15 211034](https://github.com/user-attachments/assets/066deb3b-31d0-43b8-b534-05ed30ff1ea2)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

