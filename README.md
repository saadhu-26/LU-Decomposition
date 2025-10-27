# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation. 
2.Prepare the lists from each linear equations assign in np.array(). 
3.Using the np.linalg.solve(),we can find the solutions.
4.Execute the program.

## Program:
(i) To find the L and U matrix

'''Program to find the L and U matrix.
Developed by: Saadhana A
RegisterNumber:25018432 
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix

'''Program to find the LU Decomposition of a matrix.
Developed by:Saadhana A 
RegisterNumber:25018432
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,.pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)

## Output:
![lu decomposition]()
<img width="976" height="499" alt="Screenshot 2025-10-24 at 6 04 28 PM copy" src="https://github.com/user-attachments/assets/bac44e58-6956-4804-8ab1-df59d5189749" />

<img width="989" height="283" alt="Screenshot 2025-10-24 at 6 04 53 PM" src="https://github.com/user-attachments/assets/c99a3c68-174b-48d2-8683-ab33a7e4b744" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
