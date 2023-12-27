# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open file in read mode.
### Step 2: 
 Read the text using read funcion.
### Step 3: 
Split the text using space separator.
### Step 4:  
The length of the split list should be equal to the number of words in the text file.
### Step 5: 
Now give print().
### Step 6: 
End the program.
## PROGRAM:
Developed by: Abbu Rehan
Register Number : 23010259

```
num=0
with open("file1.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![Screenshot (159)](https://github.com/Abburehan/Word-count/assets/138849336/921e303e-049d-4332-8fd0-cb9eb242e472)

## RESULT:
Thus the program is written to find the word count from a text.
