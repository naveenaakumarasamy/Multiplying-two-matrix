# Multiplying-two-matrix

## AIM:
To write a python program to multiply two matrix and to display the the product of two array

## ALGORITHM:

### Step 1:
import numpy
### Step 2:
get the user input
### Step 3:
append the inputs in array
### Step 4:
mutltiply the arrays
### Step 5:
print the product of the array

## PROGRAM: 
```python
#developed by :Naveenaa A.K
#Register number: 22003091

import numpy as np
n = int(input())
l1,l2=[],[]
for i in range(n):
    l1.append (int(input()))
for i in range(n):
    l2.append(int(input()))
array1 = np.array(l1)
array2 = np.array(l2)
product = array1*array2
print("Product of two arrays is:",product)
```
## OUTPUT:
![multiplying](https://user-images.githubusercontent.com/113497406/194262141-205cc5c1-0c42-4170-9b2d-6a6bc8af94fd.png)


## RESULT:
hence the programe runned successfully
