# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program

### Step 2: 
Import the file
 
### Step 3: 
Open the file

### Step 4:
Write the function to count the words

### Step 5: 
Print the result

### Step 6: 
End the program

## PROGRAM:
##Developed by:RAMYA P
##Reference number:23006111
~~~
import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close
~~~

### OUTPUT:
![image](https://github.com/23006111/command-line-arguments-to-count-word/assets/145981696/b4208d39-9856-4192-9934-143703fb5c4c)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
