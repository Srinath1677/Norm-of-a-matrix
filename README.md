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
# Register No:212224230274
# Developed By:Srinath YG
# 1-Norm of a Matrix
```
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)
```

# 2-Norm of a Matrix
```
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))
```
# Infinity Norm of a Matrix
```
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))
```

```
## Output:
### 1-Norm of a Matrix
![443350032-6ec31e46-2db6-4ab8-9266-6282b43ee5b1](https://github.com/user-attachments/assets/7ff67176-c209-454c-990d-69a7f04e52aa)


### 2-Norm of a Matrix
![443350572-11a6d35f-9714-46f3-9bad-1a69b0cef37a](https://github.com/user-attachments/assets/abee40af-3b1d-48e2-96c6-84fd164bfed1)


### Infinity Norm of a Matrix

![443350345-e1d7a0c5-70fd-4c1a-943d-7c51bbace23d](https://github.com/user-attachments/assets/6aa353f9-8e1a-4f49-b344-69634cf02117)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
