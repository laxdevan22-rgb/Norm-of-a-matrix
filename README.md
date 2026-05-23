# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
Write a python program to find the 1-Norm of a matrix and display the results in two decimal places.
#Developed by:Lakshita rai.V 
#RegisterNumber:212225220054
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, 1)

print("{:.2f}".format(norm))




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: V.Lakshita Rai
RegisterNumber: 212225220054
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, 2)

print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
'''
Write a program to find the Infinity of a matrix and display the result in two decimal places.
Developed by: V.Lakshita Rai
RegisterNumber: 212225220054
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, np.inf)

print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
<img width="701" height="326" alt="image" src="https://github.com/user-attachments/assets/c5d714b0-ad0e-4729-96f1-715b89e25141" />


### 2-Norm of a Matrix
<img width="797" height="397" alt="image" src="https://github.com/user-attachments/assets/06ab352f-f36d-40ce-b111-171b7f3c5f6a" />



### Infinity Norm of a Matrix
<img width="776" height="325" alt="image" src="https://github.com/user-attachments/assets/4e2860be-d387-4fd4-826f-4dac140bed73" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
