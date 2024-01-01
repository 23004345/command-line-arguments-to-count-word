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
intially make count=0
 
### Step 3: 
open the content file using command line arguments

### Step 4: 
by using for loop name the function as "line"

### Step 5: 
split the line using .split

### Step 6: 
split the line using.split

## PROGRAM:

import sys

fp=open(sys.argv[1],'r')

count=0

for line in fp

    words=line.split()
    
    count+=len(words)
    
print("Numbers of words in a file",count)    

### OUTPUT:
![Screenshot 2024-01-01 130017](https://github.com/23004345/command-line-arguments-to-count-word/assets/138849203/592ab074-7c3d-461c-a462-fa9db0f9db85)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
