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
# Register No:212222230003
# Developed By:P.V.Abishek
# 1-Norm of a Matrix
```
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: P.V.Abishek
RegisterNumber:212222230003 
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```

# Infinity Norm of a Matrix
```
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
![Screenshot 2023-06-07 133727](https://github.com/pvabishek/Norm-of-a-matrix/assets/119405626/44d857b9-4569-499d-8cbe-dc4de54dbc3c)

### 2-Norm of a Matrix
![Screenshot 2023-06-07 133736](https://github.com/pvabishek/Norm-of-a-matrix/assets/119405626/0b2660c1-f87b-4602-96fa-ba1edee6d74f)


### Infinity Norm of a Matrix
![Screenshot 2023-06-07 133745](https://github.com/pvabishek/Norm-of-a-matrix/assets/119405626/1a3c4522-d824-44a9-8e42-a4103bb45c4c)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
