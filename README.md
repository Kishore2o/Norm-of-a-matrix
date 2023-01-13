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
# 1-norm of matrix

import numpy as np
mat=np.array(eval(input()))
a=np.linalg.norm(mat,1)
norm-of-a-matrix="{:.2f}".format(a)
print(norm-of-a-matrix)

# 2-norm of matrix
import numpy as np
mat=np.array(eval(input()))
a=np.linalg.norm(mat,2)
norm-of-a-matrix="{:.2f}".format(a)
print(norm-of-a-matrix)

# infinity-norm of matrix
import numpy as np
mat=np.array(eval(input()))
a=np.linalg.norm(mat,np.inf)
norm-of-a-matrix="{:.2f}".format(a)
print(norm-of-a-matrix)

```
## Output:
![norm 1](https://user-images.githubusercontent.com/118679883/212300443-e1de258b-3513-41d2-ad86-a2a3a9456247.png)


### 2-Norm of a Matrix
![norm 2](https://user-images.githubusercontent.com/118679883/212300519-5b37149d-0a84-4f71-826a-498ddd7aa63b.png)


### Infinity Norm of a Matrix
![norm 3](https://user-images.githubusercontent.com/118679883/212300592-26095d07-07a9-4fce-9739-793eb2b59bce.png)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
