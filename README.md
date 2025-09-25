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
# Register No: 212224240162
# Developed By: SRUTHI A

#  1-Norm of a Matrix

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
<img width="1237" height="343" alt="image" src="https://github.com/user-attachments/assets/8cc4f64a-bb08-48be-adb0-e2dfb09febe7" />


### 2-Norm of a Matrix
<img width="1231" height="382" alt="image" src="https://github.com/user-attachments/assets/61c3562f-30e6-4e24-8eeb-f6186eb0c0b2" />


### Infinity Norm of a Matrix
<img width="1226" height="337" alt="image" src="https://github.com/user-attachments/assets/4029fba2-b01c-4c1a-9a3f-e5a718d89472" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
