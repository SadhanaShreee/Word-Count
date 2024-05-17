# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
Create a file story.txt in anaconda navigator.
### Step 3: 
Write a program to count the number of words in a text file.
### Step 4:  
Run the program.
### Step 5: 
Print the output.
### Step 6: 
End the program.



## PROGRAM:
```
# Word count in a Text file
# Developed by: SADHANA SHREE B
# Register number: 212223230177
num=0
with open ("story.txt","r") as f1:
   for i in f1:
     word=i.split()
     num += len(word)
   print("The number of words are in the file is",num)


```
### OUTPUT:

![Screenshot 2024-05-17 100721](https://github.com/SadhanaShreee/Word-Count/assets/144517664/26018bd6-b05d-4521-b30d-c9b050543b7e)
![Screenshot 2024-05-17 100729](https://github.com/SadhanaShreee/Word-Count/assets/144517664/44c6fd5d-8fff-40b9-8865-7790b1f1556d)



## RESULT:
Thus the program is written to find the word count from a text.
