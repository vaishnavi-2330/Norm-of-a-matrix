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
# Register No:212225230009
# Developed By:AKASHINI V
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<img width="1215" height="331" alt="Screenshot 2026-03-21 122829" src="https://github.com/user-attachments/assets/b0ebe9d3-177b-43b7-931d-8440a0f01825" />

### 2-Norm of a Matrix
<img width="1208" height="384" alt="Screenshot 2026-03-21 122842" src="https://github.com/user-attachments/assets/51d01485-fae3-4710-96c8-be79ca114853" />


### Infinity Norm of a Matrix
<img width="1214" height="323" alt="Screenshot 2026-03-21 122855" src="https://github.com/user-attachments/assets/44324f12-9aee-4771-a37c-75998fa5076d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
