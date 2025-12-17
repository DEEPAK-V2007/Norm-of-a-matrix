# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm, 1-norm and infinity-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:25017595
# Developed By:DEEPAK.V
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(round(norm,2))

# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(round(norm,2))

# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,np.inf)
print(round(norm,2))

```
## Output:
### 1-Norm of a Matrix
<br><img width="1516" height="702" alt="Screenshot 2025-12-17 143357" src="https://github.com/user-attachments/assets/85d5947e-61d9-4211-aeae-079c8888cc7d" />
<br>
<br><img width="1465" height="392" alt="Screenshot 2025-12-17 143410" src="https://github.com/user-attachments/assets/580df0b3-8714-4371-a517-eb45b6849336" />

### 2-Norm of a Matrix
<br><img width="1513" height="690" alt="Screenshot 2025-12-17 143428" src="https://github.com/user-attachments/assets/efdcdf9e-a57b-4a2b-9196-e4281c9579e8" />
<br>
<br><img width="1515" height="423" alt="Screenshot 2025-12-17 143442" src="https://github.com/user-attachments/assets/d11d2048-2f09-4a12-9233-6d9309a4d320" />

### Infinity Norm of a Matrix
<br><img width="1516" height="670" alt="Screenshot 2025-12-17 143456" src="https://github.com/user-attachments/assets/85f0d5a9-8d1b-40fe-981f-d8b9560399d6" />
<br>
<br><img width="1510" height="365" alt="Screenshot 2025-12-17 143509" src="https://github.com/user-attachments/assets/508e78b0-0766-42be-b5f5-363302569de7" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
