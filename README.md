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
![Screenshot 2024-04-16 202701](https://github.com/SarweshvaranA/LU-Decomposition/assets/146930981/2a0dd953-5ecf-428f-a1f0-ea2cb5fcd16c)

ii)
![Screenshot 2024-04-16 202711](https://github.com/SarweshvaranA/LU-Decomposition/assets/146930981/41fc95e9-8f68-4181-bda5-97cb9f54a5fd)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

