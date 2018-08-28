# How Contribute for a Github Repository

## Step 1:

### Download and Install Git

* Git Bash Download : [https://git-scm.com/downloads](https://git-scm.com/downloads)

* Git Desktop Download: [https://desktop.github.com/](https://desktop.github.com/)

## Step 2: [fork](#fork)

1. Go to the [Demo Repository](https://github.com/FOSS-UCSC/demo)
2. Click on the fork button 

![](https://image.ibb.co/fD4M7p/Capture.png)

## Step 3: [clone](#clone)
1. Now you need a copy locally in your account, so find the “SSH clone URL” in the right hand column and copy the link

![](https://github.com/FOSS-UCSC/demo/blob/master/Assets/Capture01.PNG)

2. Now open git bash and go to the folder where you need to create your local repository

ex -:
> cd ~/Desktop

3. Then type **clone command** as below with the copied link of the repository
> git clone https://github.com/FOSS-UCSC/demo
 

## Step 4:

### Do some work

Example: Write your name on a text file and save it as yourname.txt

## Step 5:

### Create a new Branch with your name

> git checkout -b yourname
 
## Step 6:

### Push your work to github

> git add .

> git commit -am "I wrote my name"

> git push origin branchname

--------------------------------------------------------------------------------
# Some Basic Details

## Fork
Get a copy of a repository from an account of someone else to your account.

## Clone
Get a copy of a repository from your github account to your local machine.
