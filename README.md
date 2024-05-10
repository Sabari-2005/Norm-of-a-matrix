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
# Register No:21223100048
# Developed By:R.Sabarinath
# 1-Norm of a Matrix
```
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```



# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: K.HEMANATH
RegisterNumber: 212223100012
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix

```


# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix
```
## Output:
![Screenshot 2024-05-10 213958](https://github.com/Sabari-2005/Norm-of-a-matrix/assets/139338709/8f2be3d5-a9f5-4339-80f9-2d71ca35ea98)
![Screenshot 2024-05-10 214018](https://github.com/Sabari-2005/Norm-of-a-matrix/assets/139338709/0b2d2864-321a-4ee0-b9b5-c7f64d38939e)
![Screenshot 2024-05-10 214034](https://github.com/Sabari-2005/Norm-of-a-matrix/assets/139338709/b0f9dfba-19b0-4942-b0e1-a486e90220c8)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
