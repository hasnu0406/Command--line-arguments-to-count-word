# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
Open the file and assign it to f1
### Step 3: 
Read the file and assign it to data
### Step 4:  
Split the data (data.split())
### Step 5: 
Print the assigned variable's length using len(word)
### Step 6: 
End the program
## PROGRAM:
```Python
Developed by: HASNA MUBARAK AZEEM
Reg No: 212223240052
import sys
count=0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word=line.split()
        count+=len(word)
print("word count in file =",count)
```
## OUTPUT:
![alt text](<exp 10.png>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
