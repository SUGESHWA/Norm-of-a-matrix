# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# 1. Get the input matrix using np.array()   
# 2. Find the 2-norm of the matrix using np.linalg.norm()
# 3. Print the norm of the matrix in two decimal places.
## Program:
```
# Register No: 212224230277
# Developed By: SUGESHWA S
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/79bdbbff-ed82-4c64-8081-2fcd0739e2ad)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/c1c141fa-d17d-494b-bbe5-5256a77f42ad)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/d1bcab19-23de-4ed1-beb0-02c0e9d28ff0)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
