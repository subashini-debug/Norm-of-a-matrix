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
'''
Program to find 2-norm of a matrix.
Developed by: Subashini K
RegisterNumber: 212225240160
'''
# 1-Norm of a Matrix
import numpy as np


mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)atrix




# 2-Norm of a Matrix


import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,2)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)


# Infinity Norm of a Matrix



import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,np,inf)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)



# Output
###  1-Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot (203)" src="https://github.com/user-attachments/assets/b5d0e985-ff33-42d2-b67e-050459c6d935" />

### 2-Norm of a Matrix

<img width="1920" height="1080" alt="Screenshot (204)" src="https://github.com/user-attachments/assets/750477d0-79ce-4f08-94ed-93cc2331a7c5" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
