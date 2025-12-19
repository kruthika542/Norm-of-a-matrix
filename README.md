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
# Register No:25012308
# Developed By:KRUTHIKA R
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b = np.linalg.norm(a,1)
print(b)


# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
b = np.linalg.norm(A,2)
print(b.round(2))


# Infinity Norm of a Matrix


import numpy as np
A=np.array(eval(input()))
b = np.linalg.norm(A,np.inf)
print(b)


```
## Output:
### 1-Norm of a Matrix

<img width="1917" height="916" alt="Screenshot 2025-12-19 090649" src="https://github.com/user-attachments/assets/d1cb3558-e374-43e1-9728-d7d2b0eba73b" />

### 2-Norm of a Matrix

<img width="1903" height="907" alt="Screenshot 2025-12-19 090727" src="https://github.com/user-attachments/assets/d1428ca6-d0d6-4f63-82d2-feb8cd833d19" />

### Infinity Norm of a Matrix

<br><img width="1919" height="921" alt="Screenshot 2025-12-19 090747" src="https://github.com/user-attachments/assets/773e40f7-74ba-4a83-98ca-9ee4c498ce3c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
