# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Create two text file. A file which has content [text.txt] to be copied to the empty [copy.txt] file

Step 2:
Using write() function copy the content from text.txt to empty file,copy.txt

Step 3:
Save and run the python program in terminal

Step 4:
The text from the text.txt file is copied to the empty file copy.txt

Step 5:
Then the text is shown in empty file copy.txt

Step 6:
The result is obtained successfully

## PROGRAM:
```
# Program to copy a text file
# Developed by: YUVARAJ B
# Reg. No: 212222230182
with open('text.txt','r') as firstfile:
    with open('copy.txt','a') as secondfile:
        for line in firstfile:
            secondfile.write(line)
```

### OUTPUT:
![243177166-1aeb24a8-57ae-4614-a8d6-e2d4482f215f](https://github.com/Yuva2005raj/copy-file/assets/118343998/8c5fa720-c811-4d5f-b9e6-8fa3f74df841)

![243177201-a2b8dd99-6d7b-468b-b682-11eba330d15b](https://github.com/Yuva2005raj/copy-file/assets/118343998/53898978-e00a-4c95-b698-af24b9b8e6fe)

![243177206-098758ac-b3b9-4bfb-9058-2d4306d61e9d](https://github.com/Yuva2005raj/copy-file/assets/118343998/448fa7ca-9e93-401d-bb88-d452dd45cd56)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
