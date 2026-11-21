# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

**STEP 1: START THE PROGRAM.**

**STEP 2: IMPORT THE NUMPY LIBRARY USING&#x20;**`import numpy as np`**.**

**STEP 3: GET THE ELEMENTS OF THE MATRIX AS INPUT FROM THE USER.**

**STEP 4: USE THE&#x20;**`np.linalg.matrix_rank()`**&#x20;FUNCTION TO FIND THE RANK OF THE GIVEN MATRIX.**

**STEP 5: DISPLAY THE RANK OF THE MATRIX.**

**STEP 6: STOP THE PROGRAM.**
## Program:
```

# Linear Algebra Exp 2
'''
Developed by: Abinaya P
Registered number: 212225230003
Write a program to find the rank for the given matrix 
[[5,-3,-10],[2,2,-3],[-3,-1,5]]
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a8346708-5309-4163-b231-ad3696cdcee0" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

