## Date:
# Exp-9: Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Start the program.

### Step 2: Create a file story.txt in anaconda navigator.
 
### Step 3: Write a program to count the number of words in a text file.

### Step 4:  Run the program.

### Step 5: Print the output.

### Step 6: End the program.

## PROGRAM:
```
##DEVELOPED BY: SURIYA M
##REFERENCE NUMBER: 212223110055

file_name='my_file.txt'
with open(file_name,'w')as file:
    file.write("Hello this is my file. \n")
num_words =0
file1 = open("my_file.txt", "r")
with open('my_file.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))

```
### OUTPUT:

![image](https://github.com/user-attachments/assets/a989c543-c52a-4cef-9b9a-8429d75bb6fa)



## RESULT:
Thus the program is written to find the word count from a text.
