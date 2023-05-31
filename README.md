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
# Register No:212222100023
# Developed By:Lokesh N

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/lokeshnarayanan/Norm-of-a-matrix/assets/119393019/955f835e-1e97-469b-ad89-0a7fa766b1f9)

### 2-Norm of a Matrix
![image](https://github.com/lokeshnarayanan/Norm-of-a-matrix/assets/119393019/9287d6da-8e93-4795-b53b-76780e4426d0)

### Infinity Norm of a Matrix
![image](https://github.com/lokeshnarayanan/Norm-of-a-matrix/assets/119393019/f9497611-8ca0-4493-89f7-2481420fa2a8)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
