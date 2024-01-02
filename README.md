
# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:import sys

### Step 2: with the file with sys.argv
 
### Step 3: create a for loop for the process

### Step 4:  count the number of words in the text

### Step 5: print the values

### Step 6: end the program

## PROGRAM:
~~~

# program to find the word count
# developed by : Panduru Somu
# Register number: 212223240111

import sys
with open(sys.argv[1],'r') as value:
    count = 0
    for i in value:
        word=i.split()
        count = len(word)
print(count)
~~~

### OUTPUT:

![Uploading Screenshot 2024-01-02 235835.png…]()


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
