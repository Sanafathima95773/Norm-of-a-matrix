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
# 1-Norm of a Matrix
```
Program to find 1-norm of a matrix.
Developed by: Sana Fathima H
RegisterNumber: 212223240145
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
norm_of_matrix="{:.2f}".format(result)
print(norm_of_matrix)
```


# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: Sana Fathima H
RegisterNumber: 212223240145
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```



# Infinity Norm of a Matrix
```
Program to find 1-norm of a matrix.
Developed by: Sana Fathima H
RegisterNumber: 212223240145
import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))
```
## Output:
## 1-Norm of a Matrix

![image](https://github.com/Sanafathima95773/Norm-of-a-matrix/assets/147084627/c3614642-b91c-4c38-b243-f72ba47d2974)


### 2-Norm of a Matrix
![image](https://github.com/Sanafathima95773/Norm-of-a-matrix/assets/147084627/25107984-aad7-4163-8295-56f8bb4db84d)


### Infinity Norm of a Matrix
![image](https://github.com/Sanafathima95773/Norm-of-a-matrix/assets/147084627/ad6da28c-2709-431d-a99f-99c4d1b1a403)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
