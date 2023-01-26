# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.
### Step 2: 
Using keyword "with" to open the requied file. 
### Step 3: 
Again using the with keyword to open the empty file.
### Step 4:  
The empty file is open by using 'W' which is used to write only.
### Step 5: 
The four function is used to take each line from the main file.
### Step 6: 
The four function is used to take each line from the main file.
## PROGRAM:
```
#Developed by: M.Jayachandran
#Reference no: 22008847
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
 ```
### OUTPUT:

![hi](https://user-images.githubusercontent.com/118447015/214830610-0a1addc2-51b0-47da-b86a-f4bd5b79332f.jpg)

![hello](https://user-images.githubusercontent.com/118447015/214830668-3e1c6501-e2a4-4e50-9f55-a88f9df7c400.jpg)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
