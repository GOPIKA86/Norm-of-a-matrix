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
# Register No:
# Developed By:
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
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-03 203305](https://github.com/user-attachments/assets/08707569-e934-4671-bf6a-fad3cac34472)

### 2-Norm of a Matrix
![Screenshot 2024-12-03 203331](https://github.com/user-attachments/assets/7d2dfa58-aa9f-4839-b243-a410ad6c1a98)

### Infinity Norm of a Matrix
![Screenshot 2024-12-03 203354](https://github.com/user-attachments/assets/8203d21b-f6bd-4bcc-b01f-258a61500715)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
