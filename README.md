# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy library as np 
2.create a matrix using np.array()
3.using scipy.linalg,lu() find l and u, also using scipy.linalg.lu_solve() get the result for lu decomposition 
4.get the output and end yhe program 

## Program:
(i) To find the L and U matrix
```

/*
Program to find the L and U matrix.
Developed by: MUKESH.P
RegisterNumber: 22008456
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MUKESH.P
RegisterNumber: 22008456
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)


## Output:
![lu math 1 op](https://user-images.githubusercontent.com/119393818/214792118-9e5f313d-0230-4802-a058-23373e6da953.png)

![lu math 2 op](https://user-images.githubusercontent.com/119393818/214792167-6043d48f-c869-444b-bf79-e9c8802f0f8f.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

