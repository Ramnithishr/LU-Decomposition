# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import maths as numpy
2. give the input values
3. use eval input
4. print the L and U matrix
  


## Program:
(i) To find the L and U matrix

```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),B)
print(X)

```

## Output:
find the L and U matrix :
![Screenshot 2024-12-10 184317](https://github.com/user-attachments/assets/6d57b41e-2ac1-4360-a7d6-5263630bbdd4)

![lu decomposition]()
![Screenshot 2024-12-10 184334](https://github.com/user-attachments/assets/f5737dcd-0678-486f-9f26-56859eda76b8)

find the LU Decomposition of a matrix:


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

