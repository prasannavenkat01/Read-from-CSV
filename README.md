# Read-from-CSV

## AIM: To write a python program for reading content from a csv file.

## ALGORITHM:
### Step 1: Import pandas as pd
### Step 2: read the csv file using read_csv method.
### Step 3: use head and tail method to get the required contents from the file
### Step 4: use len() method to count the number of rows and columns
### Step 5: print the output

## PROGRAM:
```
import pandas as pd
df = pd.read_csv('pandascsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of colunms:",len(df.axes[1])
```

## OUTPUT:
![Screenshot 2023-12-26 162429](https://github.com/prasannavenkat01/Read-from-CSV/assets/150702500/745d4cc2-52bb-4ad2-9c4e-13b149b9dc43)

## RESULT:
Thus the result was successfully verified
