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
'''program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by:SUSHMITHA S
Register number:212224230282
'''

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
'''
Program to find 2-norm of a matrix.
Developed by: sushmitha s
RegisterNumber: 212224230282
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

'''
find the Infinity of a matrix and display the result in two decimal places.
Developed by: sushmitha s
RegisterNumber: 212224230282
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))





```
## Output:
### 1-Norm of a Matrix

![Screenshot 2025-04-21 203729](https://github.com/user-attachments/assets/f6873621-e2b2-4297-a09b-bed965c15819)


### 2-Norm of a Matrix

![Screenshot 2025-04-21 203738](https://github.com/user-attachments/assets/9ed3a27f-c848-441d-91d5-3fb11319263f)


### Infinity Norm of a Matrix


![Screenshot 2025-04-21 203745](https://github.com/user-attachments/assets/a6f801ff-ff9f-41a9-bd69-3afafa3353d7)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
