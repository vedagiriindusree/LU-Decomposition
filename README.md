# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Vedagiri Indu sree
RegisterNumber: 23004520
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
a=np.array(arr)
p,l,u=lu(a)
print(l)
print(u)
## To find the LU Decomposition of a matrix
'''
'''Program to solve a matrix using LU decomposition.
Developed by: Vedagiri Indu sree
RegisterNumber: 23004520
'''
# To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
const=eval(input())
a=np.array(arr)
b=np.array(const)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)

## Output:
![image](https://github.com/vedagiriindusree/LU-Decomposition/assets/149366776/646c2a89-ac81-4f5f-9ae6-e96deed71884)

![image](https://github.com/vedagiriindusree/LU-Decomposition/assets/149366776/1654eebf-493d-4009-a635-aaf8c3f55c8c)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

