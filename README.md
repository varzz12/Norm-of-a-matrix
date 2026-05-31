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
# Register No: 212225040483
# Developed By: Varuna R
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
import ast

A = np.array(ast.literal_eval(input()))

norm1 = np.linalg.norm(A, 1)

print(f"{norm1:.2f}")



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
import ast

A = np.array(ast.literal_eval(input()))

l2_norm = np.linalg.norm(A, 2)

print(f"{l2_norm:.2f}")



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
import ast

A = np.array(ast.literal_eval(input()))

inf_norm = np.linalg.norm(A, np.inf)

print(f"{inf_norm:.2f}")




```
## Output:
### 1-Norm of a Matrix
<br><img width="1246" height="358" alt="image" src="https://github.com/user-attachments/assets/26f73df0-e30c-43ed-a4bc-f70a2aaf60e8" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1246" height="403" alt="image" src="https://github.com/user-attachments/assets/3a1a1b98-f50d-40c8-815d-329afb3f60f8" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1260" height="361" alt="image" src="https://github.com/user-attachments/assets/f76492a9-80d2-4247-ae4c-52f2749c0f62" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
