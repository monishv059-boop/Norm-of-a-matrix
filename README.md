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
# Register No:21225220066
# Developed By:MONISH V

# 1-Norm of a Matrix

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
n="{:.2f}".format(ans)
print(n)


# 2-Norm of a Matrix

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
a=np.linalg.norm(mat,2)
n="{:.2f}".format(a)
print(n)


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)



```
## Output:
### 1-Norm of a Matrix
<br>
<img width="553" height="192" alt="image" src="https://github.com/user-attachments/assets/1714d0a6-f4b9-48c6-a22a-6c5779993fd7" />

<br>

### 2-Norm of a Matrix
<br>
<img width="500" height="242" alt="image" src="https://github.com/user-attachments/assets/c9cdb4db-77cf-4299-82bb-ab7740dc0a00" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="558" height="198" alt="image" src="https://github.com/user-attachments/assets/e884c03f-43cf-4828-a6fd-ec10dbdb189b" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
