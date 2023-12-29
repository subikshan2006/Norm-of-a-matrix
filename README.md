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
# Register No:subikshan.p
# Developed By:23003939
# 1-Norm of a Matrix
import numpy as np 
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom="{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
nom="{:.2f}".format(ans)
print(nom)


```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-12-29 081653](https://github.com/subikshan2006/Norm-of-a-matrix/assets/139841805/48132fab-b871-4321-89e8-c12e4f393795)

### 2-Norm of a Matrix
![Screenshot 2023-12-29 081709](https://github.com/subikshan2006/Norm-of-a-matrix/assets/139841805/b1b042e4-fe14-4bd8-be6f-b23a596e022e)

### Infinity Norm of a Matrix
![Screenshot 2023-12-29 081716](https://github.com/subikshan2006/Norm-of-a-matrix/assets/139841805/e5aab878-f1b7-4a8f-924c-dbca2d257cba)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
