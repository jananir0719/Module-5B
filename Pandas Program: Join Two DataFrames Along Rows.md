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
```
import pandas as pd
dict1 = eval(input())
dict2 = eval(input())
df1 = pd.DataFrame(dict1)
df2 = pd.DataFrame(dict2)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
joined_df = pd.concat([df1, df2], axis=0)

print("\nJoin the said two dataframes along rows:")
print(joined_df)
```

## Output
<img width="1306" height="745" alt="image" src="https://github.com/user-attachments/assets/be4f661c-52e3-43e1-989f-393b7b1b15d5" />
<img width="996" height="505" alt="image" src="https://github.com/user-attachments/assets/9af8abbf-eb44-4ad6-894c-08fe97ade669" />
<img width="1011" height="438" alt="image" src="https://github.com/user-attachments/assets/16d24219-0eb3-435b-856c-0406f2bc0a49" />



## Result
Thus , the program has been executed succesfully.
