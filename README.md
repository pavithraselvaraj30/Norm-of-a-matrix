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
# Register no:212223230147
# Developed by:Pavithra s
# 1-Norm of a matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

Developed by: Pavithra s
RegisterNumber: 212223230147
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)


# Developed by:Pavithra s
# Register no:212223230147
# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-27 095113](https://github.com/pavithraselvaraj30/Norm-of-a-matrix/assets/149366880/e22e633e-eb82-4e52-96e6-41a75b866074)

### 2-Norm of a Matrix
![Screenshot 2024-04-27 095138](https://github.com/pavithraselvaraj30/Norm-of-a-matrix/assets/149366880/538636ce-3068-4067-9143-8c9787051861)

### Infinity Norm of a Matrix
![Screenshot 2024-04-27 095158](https://github.com/pavithraselvaraj30/Norm-of-a-matrix/assets/149366880/df6ff0e9-2567-4bff-ac6e-4b5a14d8d908)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
