# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.

### Step 2:
Open the required file by using the function "with"

### Step 3:
Then use the laptop to assign the i value in the file.

### Step 4:
Using split function to spilt the words

### Step 5:
Finding the given length of the words by using len() fuction.

### Step 6:
Calling the function and Printing the number of words.
## PROGRAM:
```
'''Program to count the words in a file
Developed by:Pravin raj.A
Register Number: 212222240079
'''

fname=input("enter the file name:")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
```
### OUTPUT:

![Screenshot 2023-06-03 200247](https://github.com/Apravinraj/Word-count/assets/118707879/28b39bb7-1c6e-4f32-8638-47ab37b1a07b)


## RESULT:
Thus the program is written to find the word count from a text.
