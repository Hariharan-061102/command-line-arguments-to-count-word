# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Give file name to read

### Step 2:
Now read the content in the file

### Step 3:
use split()

### Step 4:
Now read the no.of words in file

### Step 5:
Print number of words present in given file

### Step 6:
End of the program
## PROGRAM:
~~~
#Name:M.Hariharan
#Reg.No:212221230034
#Ref.No:21005392

import sys 
with open (sys.argv[1],"r") as f:
    num_words = 0
    for i in f:
        word = i.split()
        num_words += len(word)
print("Word count in file = ",num_words)
~~~

### OUTPUT:

![output](rec.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
