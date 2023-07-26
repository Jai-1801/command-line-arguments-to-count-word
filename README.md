# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
Then decleare count is equal to 0
### Step 3: 
read the file with python file name
### Step 4:  
Splitting the word
### Step 5: 
After splitting count the number of words in the line
### Step 6: 
In last statement give the print statement
## PROGRAM:
```
#word count from the contents of a file using command line arguments.
#Developed by : Jai Surya
#Register no: 23002572 

import sys
f=open(sys.argv[1],'r')
a=f.read().split()
print(len(a))
```
### OUTPUT:
![out](/pd.png)

![out](/pc.png)

![out](/pa.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
