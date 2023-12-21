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
```
# Register No: 212223230132
# Developed By: NARAMALA KUMARTEJA
# 1-Norm of a Matrix

import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/KumarTeja751/Norm-of-a-matrix/assets/144947756/b16a1981-07e3-4624-b50f-62296bfb0b79)


### 2-Norm of a Matrix
![image](https://github.com/KumarTeja751/Norm-of-a-matrix/assets/144947756/f1304673-7922-480b-bf5e-2c51bf7f0abe)


### Infinity Norm of a Matrix
![image](https://github.com/KumarTeja751/Norm-of-a-matrix/assets/144947756/08cd1728-464f-4263-9860-9f9e19c125e8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
