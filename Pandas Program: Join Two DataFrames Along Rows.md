# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

Add code here
~~~
import pandas as pd
data1 = pd.DataFrame(eval(input()))
data2 = pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(data1)
print("-------------------------------------")
print(data2)
result=pd.concat([data1,data2],axis=0)
print("\nJoin the said two dataframes along rows:")
print(result)
~~~
## Output
<img width="1193" height="812" alt="image" src="https://github.com/user-attachments/assets/af97fd0d-594b-4ec2-b4c8-dd540bac8c82" />

## Result
Thus,the Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is created successfully.
