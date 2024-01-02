# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
## Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
## Step 3:
Read the file using read() method.
## Step 4:
Use split() method to split the file content into words.
## Step 5:
Use len() to find the total words.
## Step 6:
Run the program to determine the number of words in the file created.
## PROGRAM:
'''

#Program to find the Word Count using command line arguments

#Developed by:ajina joshpin

#register Number:23013547

fname=input("enter the file name")

num_words=0

with open(fname, 'r') as f:

   for line in f:

      words=line.split()

num_words+=len (words)

print('Number of words: ',num_words)

'''

### OUTPUT:
![Screenshot 2024-01-02 145427](https://github.com/ajinajoshpin/command-line-arguments-to-count-word/assets/148514578/4fcaf1a4-77e4-4554-9155-6ba7b9f71555)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
