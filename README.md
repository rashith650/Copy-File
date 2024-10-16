
## DATE:
## Ex No 11 -  Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output
## PROGRAM:
```




#Program for copying the contents from one file to another file.
#Developed by MOHAMED RASHITH S
#Reg num : 24001082


with open("file1.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)















```
## OUTPUT:
### file.txt
![Screenshot (131)](https://github.com/user-attachments/assets/66c04663-0985-40d5-adc6-3dc226354237)

### Python File Execution

![Screenshot (13)](https://github.com/user-attachments/assets/d0c86803-e26b-4704-8ed6-213103231c47)

### copy.txt
![Screenshot (132)](https://github.com/user-attachments/assets/1d201e09-d62a-482b-8eef-fa8a5f164eaf)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
