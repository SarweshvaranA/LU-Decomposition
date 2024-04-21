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
'''Program to find L and U matrix using LU decomposition.
Developed by: SARWESHVARAN A
RegisterNumber: 212223230198
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SARWESHVARAN A
RegisterNumber: 212223230198
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
b=np.array(eval(input()))
sol=np.linalg.solve(matrix,b)
print(sol)
```

## Output:
i)
![LU decomposition](<LU decompostion 1.png>) 
ii)
![LU decomposition](<LU decomposition 2.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

