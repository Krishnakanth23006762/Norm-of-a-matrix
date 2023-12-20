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
```python
'''
Program to find 2-norm of a matrix.
Developed by: B.KRISHNAKANTH
RegisterNumber: 23006762
'''
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/Krishnakanth23006762/Norm-of-a-matrix/assets/138849446/bc1edd33-2814-4033-b1c7-d9b71397aec0)


### 2-Norm of a Matrix

![image](https://github.com/Krishnakanth23006762/Norm-of-a-matrix/assets/138849446/4d51f8b0-8d52-45ea-b21f-a0dd45f21a00)


### Infinity Norm of a Matrix

![image](https://github.com/Krishnakanth23006762/Norm-of-a-matrix/assets/138849446/7ff4d2de-f347-4355-861e-7cc784a1d66c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
