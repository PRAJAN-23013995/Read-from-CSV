# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.

## ALGORITHM:
Step 1:
Load the CSV into a DataFrame.

Step 2:
Print the number of contents to be displayed using df.head().

Step 3:
The number of rows returned is defined in Pandas option settings.

Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by:PRAJAN P
#Register Number: 212223240121

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![csv file](https://github.com/PRAJAN-23013995/Read-from-CSV/assets/150313345/a607e309-f969-4fd5-837c-5019997fb22a)

## RESULT:
Thus the program is written to read the csv file.
