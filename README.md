# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the required file by using the function 'with'
### Step 2: 
Use a for loop to iterate the content in the file
### Step 3: 
Use the split function to split the words
### Step 4:  
Find the given length of the words using len() function
### Step 5: 
Call the function
### Step 6: 
Print the number of words
## PROGRAM:
```
#Program to find the word count
#Developed by: Shehan Shajahan
#Register Number: 23008724
num=0
with open("sample.txt","r") as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
print("The number of words in the file: ",num)
```
### OUTPUT:
![Screenshot 2024-01-02 165356](https://github.com/shehanshajahan/Word-count/assets/139317389/be871b44-4d47-432a-8580-68537094c5a8)
![Screenshot 2024-01-02 171949](https://github.com/shehanshajahan/Word-count/assets/139317389/a216e8c1-7def-46ae-9f70-50d7495acf55)
## RESULT:
Thus the program is written to find the word count from a text.
