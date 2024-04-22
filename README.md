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
# Register No:
# Developed By:
# 1-Norm of a Matrix
```
'''
program to find 1-norm of a matrix.
Developed by: Veslin Anish A
Registerno:212223240175
'''
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))

```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: veslin anish.A
RegisterNumber: 212223240175
'''
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(two_matrix))


```
# Infinity Norm of a Matrix
```
'''
program to find infinity of a matrix and display the result in two decimal places.
Developed by:Veslin Anish A
Registerno:212223240175
'''
import numpy as np
matrix=eval(input())
infinity_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(infinity_matrix))




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![WhatsApp Image 2024-04-22 at 17 36 25_7461a9c0](https://github.com/veslin23000303/Norm-of-a-matrix/assets/151148539/32a18142-cd4d-4c20-8595-71e4a06eead0)


### 2-Norm of a Matrix
<br>
<br>
<br>
![WhatsApp Image 2024-04-22 at 17 36 51_1a970475](https://github.com/veslin23000303/Norm-of-a-matrix/assets/151148539/584e76ba-c88e-4ed5-9f55-9ca7ee80f11e)


### Infinity Norm of a Matrix
<br>
<br>
<br>
![WhatsApp Image 2024-04-22 at 17 37 17_d8e795e6](https://github.com/veslin23000303/Norm-of-a-matrix/assets/151148539/aa55ae80-5b6e-4168-9840-c7f5d0a8458d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
