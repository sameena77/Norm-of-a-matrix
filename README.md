## Exp7 Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.  Hardware – PCs
2.  Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 2305002019
# Developed By: Sameena J

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output
![1 nom](https://github.com/sameena77/Norm-of-a-matrix/assets/155620541/db8db9d1-ee67-485a-99fb-cb64ccaa85d4)
![2 nom](https://github.com/sameena77/Norm-of-a-matrix/assets/155620541/f936b81d-3287-4e51-b3c1-59b5c3bcfa81)
![3 nom](https://github.com/sameena77/Norm-of-a-matrix/assets/155620541/a16c5be9-ee80-43de-89ae-6ebac27dad66)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
