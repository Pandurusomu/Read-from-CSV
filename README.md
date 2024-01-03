# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1: import pandas as pd
### Step 2: read the use theb csv file using read_csv
### Step 3: print the head of the file using head function
### Step 4: print the tail part of the file using tail function
### Step 5: if you want print the number of rows and columns using the following function  

## PROGRAM:
~~~
import pandas as pd

x=pd.read_csv(r'C:\Users\admin\OneDrive\for python\py\pandas.py\data.csv')

print(x.head())
print(x.tail())
print('Number of rows : ',len(x.axes[0]))
print('Number of columns : ',len(x.axes[1]))
~~~

## OUTPUT:
![WhatsApp Image 2024-01-03 at 07 49 33_5d83e164](https://github.com/Pandurusomu/Read-from-CSV/assets/148988619/71321c59-ec67-49f9-a9ce-fa3c7f18072e)



## RESULT:
we got output


