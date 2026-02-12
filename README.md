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
# Register No:212225240096
# Developed By:NARENDRA KRISHNAN KS
# 1-Norm of a Matrix

import numpy as np
j=np.array(eval(input()))
u=np.linalg.norm(j,1)
print("{:.2}".format(u))


# 2-Norm of a Matrix
import numpy as np
h=np.array(eval(input()))
i=np.linalg.norm(h,2)
print("{:.2f}".format(i))





# Infinity Norm of a Matrix
import numpy as np
ju=np.array(eval(input()))
hi=np.linalg.norm(ju,np.inf)
print("{:.2f}".format(hi))




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="681" height="214" alt="image" src="https://github.com/user-attachments/assets/48cf7239-9fb7-4d51-af5b-ff62a04363b8" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="536" height="199" alt="image" src="https://github.com/user-attachments/assets/688304cc-7d8b-4adf-b23d-9fabfdfbfb0f" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="534" height="219" alt="image" src="https://github.com/user-attachments/assets/1d2b5645-3287-43da-9215-d471bb6f5259" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
