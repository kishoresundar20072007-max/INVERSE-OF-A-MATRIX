# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy module to perform matrix operations.
### Step 2: Create the given matrix using np.array() and store it in a variable.
### Step 3: Use the np.linalg.inv() function to find the inverse of the matrix.
### Step 4: Display the inverse matrix and end the program

## Program:
```

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[2, 1, 1],
              [1, 1, 1],
              [1, -1, 2]])

solution = np.linalg.inv(A)

print(solution)      
```
## Output:
<img width="1496" height="855" alt="Screenshot 2026-08-11 124056" src="https://github.com/user-attachments/assets/b7eed0b9-142a-4530-b5f1-3797cd5d0f03" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

