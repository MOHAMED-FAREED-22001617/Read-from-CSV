# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of row returned is defined in pandas option settings.
### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```python
#DEVELOPED BY:MOHAMED FAREED.F
#REGISTER NO: 22001617
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```
## OUTPUT:
![Screenshot from 2023-01-26 11-35-37](https://user-images.githubusercontent.com/121412904/214805522-8a0f6902-0544-447a-86fc-43c24dabe9ea.png)

## RESULT:
Thus the program executed successfully for read csv file.
