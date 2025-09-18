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
# Register No:212224110041
# Developed By:NAVINKUMAR.S
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
Norm_of_matrix=f"{ans:.2f}"
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

<img width="1215" height="852" alt="image" src="https://github.com/user-attachments/assets/d541e733-198a-432f-a5af-6de3de8a0a14" />


### 2-Norm of a Matrix

<img width="1143" height="931" alt="image" src="https://github.com/user-attachments/assets/8f37264b-e01b-4e53-bd08-c2d5a962bb8f" />


### Infinity Norm of a Matrix

<img width="1148" height="826" alt="image" src="https://github.com/user-attachments/assets/9efdb280-3d95-4da6-9681-a6a70df87d6d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
