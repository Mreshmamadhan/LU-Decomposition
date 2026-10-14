# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm : 
### 5.a
### Step 1. Start the program and import the required Python libraries
### Step 2. Read the input matrix and initialize L and U
### Step 3. Calculate the L and U matrices using the LU Decomposition method
### Step 4. Display the L and U matrices and stop the program
### 5.b
### Step 1. Start the program and import the required Python libraries
### step 2. Read the input matrix and initialize L and U
### Step 3. Calculate the L and U matrices using the LU Decomposition method
### Step 4. Display the L and U matrices and stop the program
 
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Reshma M
RegisterNumber:26018352
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Reshma M 
RegisterNumber:26018352
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

*/
```

## Output:
![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

