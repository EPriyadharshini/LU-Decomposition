# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy libravary using import statement
2. from scipy package import lu()
3. get input from user and pass it as an array
4. get p,lu matrix using lu()
5. print l and u matrix

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:Priyadharshini.E
RegisterNumber:23012593
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by:Priyadharshini.E 
RegisterNumber:23012593 
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
l=lu_solve((lu,piv),b)
print(l)

## Output:
(i) To find the L and U matrix
<img width="389" alt="image" src="https://github.com/EPriyadharshini/LU-Decomposition/assets/144870831/be28ef40-ce63-4063-a70f-3a3d42486dba">
(ii) To find the LU Decomposition of a matrix
<img width="271" alt="image" src="https://github.com/EPriyadharshini/LU-Decomposition/assets/144870831/3bd5a7cf-82fd-4c5e-906b-90168234519c">


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

