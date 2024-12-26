# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Program-1

```
1.Get the input matrix using np.array()
2.Find the 1-norm of the matrix using np.linalg.norm()
3.Print the norm of the matrix in two decimal places.
```
Program-2
```
1.Get the input matrix using np.array()
2.Find the 2-norm of the matrix using np.linalg.norm()
3.Print the norm of the matrix in two decimal places.
```
Program-3
```
1.Get the input matrix using np.array()
2.Find the infinity-norm of the matrix using np.linalg.norm()
3.Print the round off value for the norm of the matrix.
```

## Program:
## 1-Norm matrix
```
# Register No: 24006285
# Developed By: PRAGATHI KUMAR
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## 2-Norm matrix
```
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Infinity Norm of a matrix
```
import numpy as np
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,2)
print(round(ans))


```
## Output:
### 1-Norm of a Matrix

![alt text](<Screenshot from 2024-12-15 12-06-31.png>)



### 2-Norm of a Matrix
![alt text](<Screenshot from 2024-12-15 12-07-38.png>)


### Infinity Norm of a Matrix
![alt text](<Screenshot from 2024-12-15 12-08-09.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
