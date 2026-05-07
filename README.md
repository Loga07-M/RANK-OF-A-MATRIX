# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Import the numpy module to use the built in functions for calculations 
### Step 2: Get the input from the user
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:End the program 
## Program:

```
#Program to find the rank of a matrix.
#Developed by: LOGA SRI M 
#RegisterNumber: 212225230153
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
MatrixA=np.array([[5,-3,10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(MatrixA)
print(rank)
```
## Output:

<img width="877" height="302" alt="Screenshot 2026-05-07 124718" src="https://github.com/user-attachments/assets/9027bcbb-1758-4290-be6b-d7c4bde10758" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
