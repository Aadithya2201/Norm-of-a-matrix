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
# Register No:23006361
# Developed By:AADITHYA R
# 1-Norm of a Matrix

'''
Promgram to find 1-norm of a matrix.
Developed by: Aadithya.R
Register Number: 23006361
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)

# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Aadithya.R
RegisterNumber: 23006361
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)

# Infinity Norm of a Matrix

'''
Program to find infinity of a matrix.
Developed by: Aadithya.R
RegisterNumber: 23006361
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-12-27 144706](https://github.com/Aadithya2201/Norm-of-a-matrix/assets/145917810/93371bdf-8b94-46cb-a0f0-7a97335f395f)


### 2-Norm of a Matrix

![Screenshot 2023-12-27 144723](https://github.com/Aadithya2201/Norm-of-a-matrix/assets/145917810/88942029-239d-4620-bae3-1ac779e72aaa)

### Infinity Norm of a Matrix

![Screenshot 2023-12-27 144739](https://github.com/Aadithya2201/Norm-of-a-matrix/assets/145917810/29980ad8-f411-4fcd-88a8-3f42deac2109)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
