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
# Register No:25018016
# Developed By:DIVYA PRIYA.S

```
```
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,1)
print(norm)


# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")


# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,np.infty)
print(norm)


```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1906" height="930" alt="Screenshot 2025-11-26 112313" src="https://github.com/user-attachments/assets/dfb7ad72-0eac-478a-9bf4-999518231581" />

<br>
<img width="1907" height="597" alt="Screenshot 2025-11-26 112329" src="https://github.com/user-attachments/assets/9b5d26f8-d6dd-43db-9d11-7124abd1cc31" />

<br>

### 2-Norm of a Matrix
<br>
<img width="1907" height="1007" alt="Screenshot 2025-11-26 112353" src="https://github.com/user-attachments/assets/0cff1dbf-10e9-4f7d-8655-4d19e7be5cc2" />

<br>
<img width="1876" height="613" alt="Screenshot 2025-11-26 112409" src="https://github.com/user-attachments/assets/4ae5126a-2723-4dcb-b70f-b6da4c72fe24" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="1907" height="873" alt="Screenshot 2025-11-26 112425" src="https://github.com/user-attachments/assets/d9ba5553-d64c-480b-936b-43058c3184a9" />

<br>
<img width="1907" height="563" alt="Screenshot 2025-11-26 112437" src="https://github.com/user-attachments/assets/5cb23903-cd24-4fd1-b8d2-4130e60f5d9f" />

<br>

## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
