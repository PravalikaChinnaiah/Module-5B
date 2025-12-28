# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

Add code here
~~~
import numpy as np
arr=np.array(eval(input()))
new_col=np.array(eval(input()))
print("Printing Original array")
print(arr)
print("Array after deleting column 2 on axis 1")
del_col=np.delete(arr,1,axis=1)
print(del_col)
print("Array after inserting column 2 on axis 1")
insert_col=np.insert(del_col,1,new_col,axis=1)
print(insert_col)

~~~
## Output
<img width="1147" height="743" alt="image" src="https://github.com/user-attachments/assets/22e7db49-3794-49a3-8ae0-4de3c0c34e97" />


## Result
Thus,the Python program that deletes the second column from a given 2D array and inserts a new column at the same position is created successfully.
