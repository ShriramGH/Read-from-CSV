# Read-from-CSV

## AIM:
To write a python program to read data from CSV file.

## ALGORITHM:

### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.

## PROGRAM:
'''

Developed By : Shriram S 

Referance No. : 22008494

'''

import pandas as pd

f=pd.read_csv('nba.csv')

print(f.head(10))

print(f.tail())

print('Row:',len(f.axes[0]))

print('Col:',len(f.axes[1]))

## OUTPUT:
![6 Sram](https://user-images.githubusercontent.com/117991122/214779803-6ff87c07-078d-474e-9983-5fda55945cc6.png)


## RESULT:
A python program to read data from CSV files has been created successfully.
