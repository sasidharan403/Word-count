# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1::Start

### Step 2: Declare a variable count equal to 0.
 
### Step 3: Open the required text file in read mode as text.(any name can beused).

### Step 4:  Loop until variable i in file text.

### Step 5: Declare variable word = i.split().

### Step 6: Process count+=len(word)End loop

## PROGRAM:
#Developed by:-sasidharan
#Reference number:-21004178
count =0
with open('recordText','r') as text:
for i in text:
word = i.split()
count+=len(word)
print('The number of words in the file are :',count)

### OUTPUT:
![output](1.png)

![output](2.png)

## RESULT:
Thus the program is written to find the word count from a text.
