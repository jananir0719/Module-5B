# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
import numpy as np
data = eval(input())
labels=eval(input())
df = pd.DataFrame(data, index=labels)
print(df)
```

## Output
<img width="1260" height="433" alt="image" src="https://github.com/user-attachments/assets/3b2ecf7a-66de-41ae-98e6-2381c9aea55b" />
<img width="1262" height="422" alt="image" src="https://github.com/user-attachments/assets/643f055e-b28c-4dbe-b8ac-58f6eb934670" />


## Result
Thus , the program has been executed succesfully.
