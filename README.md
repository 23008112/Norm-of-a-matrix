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

# 1-Norm of a Matrix
```
#Program to find 2-norm of a matrix
#Developed by:R.SANJANA
#Register Number:23008112

import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
#Program to find 2-norm of a matrix.
#Developed by: R.SANJANA
#RegisterNumber: 23008112

import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix
```
#Program to find Infinity norm of a matrix
#Developed by:R.SANJANA
#Register Number:23008112

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-23 233044](https://github.com/23008112/Norm-of-a-matrix/assets/138972470/aa3b0054-ab3b-4ec6-b168-6651841e792d)

### 2-Norm of a Matrix
![Screenshot 2023-12-23 233109](https://github.com/23008112/Norm-of-a-matrix/assets/138972470/ff18a5c5-4bfc-43f3-bca1-6c68d16408f7)

### Infinity Norm of a Matrix
![Screenshot 2023-12-23 233149](https://github.com/23008112/Norm-of-a-matrix/assets/138972470/588510e8-08e8-4429-8c3b-a4d73a7930eb)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
