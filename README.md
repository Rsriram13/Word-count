# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2:
Read the text using read() function.
### Step 3:
Split the text using space separator.We assume that words in a sentance are separted by a space
character.
### Step 4:
The length of the split list should equal the numbers of words in the test file.
### Step 5:
You can refine the count by cleaning the string prior to splitting or validating the words after
splitting.
### Step 6:
End the program.

## PROGRAM:
```
#Program to find the number of words in a txt file.
#Developed by: Sriram R
#Reg no: 212223230215
num=0
with open("file1.txt","r") as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
print("The number of words in the file is ",num)
```
### OUTPUT:
![output](https://github.com/Rsriram13/Word-count/assets/145742823/1fb6bffc-873f-4a03-8a7c-d19c15a4d91b)

![output](https://github.com/Rsriram13/Word-count/assets/145742823/ae19eb57-ee4d-4424-b692-dcb0db604592)


## RESULT:
Thus the program is written to find the word count from a text.
