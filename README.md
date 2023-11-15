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
'''
# Register No:23010238
# Developed By:Sundaramurthy M
# 1-Norm of a matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
'''

# 2-Norm of a Matrix

'''
# Register No:23010238
# Developed By:Sundaramurthy M
# 1-Norm of a matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
'''

# Infinity Norm of a Matrix
'''
# Register No:23010238
# Developed By:Sundaramurthy M
# 1-Norm of a matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
'''


```
## Output:
<img width="1440" alt="Screenshot 2023-11-15 at 10 34 11 PM" src="https://github.com/Murthy46/Norm-of-a-matrix/assets/145112768/79c9e48c-2384-4894-be1c-07a603e90a9e">

<img width="1440" alt="Screenshot 2023-11-15 at 10 34 19 PM" src="https://github.com/Murthy46/Norm-of-a-matrix/assets/145112768/e23940fd-d922-4c9d-be5b-7b76a01d1bc2">

<img width="1440" alt="Screenshot 2023-11-15 at 10 34 28 PM" src="https://github.com/Murthy46/Norm-of-a-matrix/assets/145112768/1d8f31d3-05a5-4e49-af83-b3f476e79516">



### 1-Norm of a Matrix

<img width="859" alt="Screenshot 2023-10-12 at 8 37 45 PM" src="https://github.com/Murthy46/Norm-of-a-matrix/assets/145112768/1e8dcbff-bc94-4302-97cb-82ca7525b3f0">

<br>
<br>
<br>

### 2-Norm of a Matrix

<img width="843" alt="Screenshot 2023-10-12 at 8 37 56 PM" src="https://github.com/Murthy46/Norm-of-a-matrix/assets/145112768/13babf20-694f-474e-b351-78e395fb9a22">

<br>
<br>
<br>

### 3-Infinity Norm of a Matrix

<img width="756" alt="Screenshot 2023-10-12 at 8 38 07 PM" src="https://github.com/Murthy46/Norm-of-a-matrix/assets/145112768/c5d1cf18-6b39-4c1f-8fab-d51c9f25a749">

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
