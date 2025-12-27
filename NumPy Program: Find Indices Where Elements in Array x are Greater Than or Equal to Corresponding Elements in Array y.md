# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

Add code here
~~~
import numpy as np
n,m =map(int, input().split())

A = []
for _ in range(n):
    A.append(list(map(int, input().split())))
A = np.array(A, dtype=np.int64)

B=[]
for _ in range(n):
    B.append(list(map(int, input().split()))) 
B = np.array(B, dtype=np.int64) 

print(np.add(A,B))
print(np.subtract(A,B))
print(np.multiply(A,B))
print(np.floor_divide(A,B))
print(np.mod(A,B))
print(np.power(A,B))
~~~
## Output
<img width="1021" height="732" alt="image" src="https://github.com/user-attachments/assets/ff277320-96f2-4a39-a5a9-03e2b84badfd" />



## Result
Thus,the Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y` is created successfully.
