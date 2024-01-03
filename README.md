
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
![image](https://github.com/Pandurusomu/command-line-arguments-to-count-word/assets/148988619/53df4832-7d96-46e2-8daa-a69154aa1aef)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
