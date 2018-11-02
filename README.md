# Predictive-Model-Healthcare
Toy Projects of building predictive models in healthcare

## 1. [ Github Setup](#git)
## 2. [ Python from Bittiger](#tiger)
   ###  1. [Python Fundamentals](#fun)
   ###  2. [Example of Predictive Model](#predict)
   ###  3. [Other Topics using Python](#new)
## 3. [ Python from Dataquest](#quest)
   ### 1. [Data Science](#science)
   ### 2. [Data Engineer](#engineer)
    
<a name="git"></a>
## 1. Github Setup

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

There are two references here, [Reference 1](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/) and [Reference 2](https://help.github.com/articles/adding-a-file-to-a-repository/)

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

<a name="predict"></a>
### Example of Predictive Model

https://code.savvysherpa.com/wouyang/Python-Tool-Box/blob/master/Uber_Rider_Churn_Supervised_Learning.ipynb

<a name="new"></a>
### Other Topics using Python

| Domain             | Folder/File|   Notebook Address   | 
|--------------------|------------|----------------------|
| NLP                | Folder     |                      |
| Recommendation     | Folder     |                      | 
|                    | Yes        |                      | 


<a name="quest"></a>
## 3. Python from Dataquest
<a name="science"></a>
### Data Science

