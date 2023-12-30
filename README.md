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
# Register No: 23014165
# Developed By: TH KARTHIK KRISHNA

# 1-Norm of a Matrix
import numpy as np
a =np.array(eval(input()))
b=np.linalg.norm(a,1)
norm_of_matrix = "{:.2f}".format(b)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
norm_of_matrix='{:.2f}'.format(b)
print(norm_of_matrix)





# Infinity Norm of a Matrix


import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
norm_of_matrix="{:.2f}".format(b)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/karthikkrishna16/Norm-of-a-matrix/assets/148514663/d8fa41af-8e13-4d86-996c-5cc0b2bc602c)


### 2-Norm of a Matrix

![image](https://github.com/karthikkrishna16/Norm-of-a-matrix/assets/148514663/f1839bb1-d9f2-4c22-af33-9a378596dc78)

### Infinity Norm of a Matrix
![image](https://github.com/karthikkrishna16/Norm-of-a-matrix/assets/148514663/78e1f1ee-a993-4328-a8d1-fd46003db0b1)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
