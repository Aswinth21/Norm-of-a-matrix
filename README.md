# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### step 1:
Get the input matrix using np.array() 
### step 2:	 
Find the 2-norm of the matrix using np.linalg.norm()
### step 3:	 
Print the norm of the matrix in two decimal places.
	 
## Program:
```Python
# Register No: 212222230015
# Developed By: Aswinth.p
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,1)
norm="{:.2f}".format(solu)
print(norm)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,2)
norm="{:.2f}".format(solu)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
solu=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(solu)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Aswinth21/Norm-of-a-matrix/assets/120236638/ef693ca6-4ae7-4b74-a3fb-fcd7ea40c64e)

### 2-Norm of a Matrix
![image](https://github.com/Aswinth21/Norm-of-a-matrix/assets/120236638/71d9e1a6-87ff-4c7d-aefe-626759d9ad38)

### Infinity Norm of a Matrix
![image](https://github.com/Aswinth21/Norm-of-a-matrix/assets/120236638/23e816ff-8e6e-43ff-8e5b-8d1f44f88b48)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
