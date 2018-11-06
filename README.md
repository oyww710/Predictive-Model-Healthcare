# Predictive-Model-Healthcare
Toy Projects of building predictive models in healthcare

## 1. [ Predict Readmission using Diabetes Dataset](#diabete)

[DataLink](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008#) 

   ###  1. [Python Notebook](#Py1)
   ###  2. [R Notebook](#R1)
   
## 2. [ Predict Medical Appointment No Shows](#appointment)

[DataLink](https://www.kaggle.com/joniarroba/noshowappointments) 

   ###  1. [Python Notebook](#Py2)
   ###  2. [R Notebook](#R2)
   
## 3. [ Python from Dataquest](#quest)
   ### 1. [Data Science](#science)
   ### 2. [Data Engineer](#engineer)
    
<a name="diabete"></a>
## 1. Predict Readmission using Diabetes Dataset

<a name="Py1"></a>


There is an example here below

![Screenshot](Snapshot_Git_Push.png)

Notation: You need to determine your origin each time you did something

Step 1: firstly locate to what you save your local files

Step 2: initialized existing Git repository 

   ```bash
      $ git init
      $ git add .   #add the newly files 
      $ git commit -m "Add existing file" #Commit your adding
   ```

Step 3: Make your github address(clone from github) as the remote origin

   ```bash
      $ git remote add origin https://code.savvysherpa.com/wouyang/Python-Tool-Box.git
   ```

Step 4: Mirror all documents in local to remote origin (your github address)

   ```bash
      $ git push --mirror https://code.savvysherpa.com/wouyang/Python-Tool-Box.git 
   ```

Step 5: How to do some changes and push back to your remote github?

Each time, you need to clone the current content from the github. The code is as followings:

   ```bash
      $ git clone https://code.savvysherpa.com/wouyang/Python-Tool-Box.git
   ```

After that, you can use 'git ls-files' to check the exact name for each file in your github. 

   ```bash
      $ git ls-files
   ```

If you want to change folder name, just do 'git mv -f Python Fundamentals Python_Fundamentals', if you want to change the file name, just remove '-f' from above command line.

Then

   ```bash
      $ git add .
      $ git commit -m "Python_Fundamentals"
      $ git status
      $ git push
   ```

And the changes will be commited to github.

<a name="tiger"></a>
## 2. Python from Bittiger
<a name="fun"></a>
### Python Fundamentals
Click on this folder - [Python_Fundamentals] (https://code.savvysherpa.com/wouyang/Python-Tool-Box/tree/master/Python_Fundamentals)



