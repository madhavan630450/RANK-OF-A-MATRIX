# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start: Take a matrix A as input.

### Step 2: Transform the matrix to its row echelon form (or use a built-in function).

### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4: Count the number of non-zero rows in the row echelon form.

### Step 5: This count is the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: MARIMUTHU MATHAVAN
#RegisterNumber: 212224230153
import numpy as np
A = np.array([[1,2,3],[3,6,9]])
result = np.linalg.matrix_rank(A)
print(result)
```
## Output:
![Screenshot (52)](https://github.com/user-attachments/assets/b953ef96-8a57-46d8-a1b5-168fb4261c9c)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

