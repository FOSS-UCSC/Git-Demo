# How To Contribute for a Github Repository

## Step 1:

### Download and Install Git

* Git Bash Download : [https://git-scm.com/downloads](https://git-scm.com/downloads)

* Git Desktop Download: [https://desktop.github.com/](https://desktop.github.com/)

## Step 2: [fork](#fork)

1. Go to the [Demo Repository](https://github.com/FOSS-UCSC/demo)
2. Click on the **fork button** 

![](https://image.ibb.co/fD4M7p/Capture.png)

## Step 3: [clone](#clone)
1. Now you need a copy locally in your account, so find the “SSH clone URL” in the right hand column and copy the SSH link

![](https://github.com/FOSS-UCSC/demo/blob/master/Assets/Capture01.PNG)

2. Now open **git bash** and go to the folder where you need to create your local repository

ex -:
> cd ~/Desktop

3. Then type **clone command** as below with the copied link of the repository
> git clone https://github.com/FOSS-UCSC/demo
 
## Step 4:

1. Now go to the newly created folder named *"demo"* in the desktop or location that you specified before
2. Now you can do any thing you want inside that folder. For this tutorial, open **test.txt** and do appropriate changes

## Step 5: [Git Track Files](#git-track-files)

1. Type the following command in the Git Bash
> cd ./demo

> git add .

for tracking all the files use **Dot**. If you want, you can give the specific file name to track

## Step 6: [Git Commit](#git-commit)

1. Type the following command in the Git Bash
> git commit -m "I wrote my name and username"

## Step 7: [Git Push](#git-push)

If this is the first time of pushing, you have to [make a SSH key](#git-make-a-ssh-key) for your account.

1. Type the following command in the Git Bash
> git push origin master

## Step 8: [Pull Request](#git-pull-request)

Now you have forked a repository from FOSS-UCSC to your account, created a clone repository to your local machine from that forked repository, did some changes and pushed it to the github repository in your account. Now we have to make your changes in the repository of FOSS-UCSC too.

1. Go to the "demo" github repository in your account and click the pull request link
![](https://github.com/FOSS-UCSC/demo/blob/master/Assets/Capture02.PNG)

2. Do the rest of things in appropriate way and make a new PR. After you make a PR we can review it and merge to our repository


--------------------------------------------------------------------------------
# Some Basic Details

## Fork
Get a copy of a repository from an account of someone else to your account.

## Clone
Get a copy of a repository from your github account to your local machine.

## Git Track Files
Git is a system which can to track the changes of your files.

## Git Commit
Commiting is something similar like saving changes inside the git.

## Git Push
When you do some changes on the local repository in your machine, that's not do any change in the repository of your github account. To do that changes you need to push it.
> git push origin <branch name>

## Git Create a new Branch
Branching is a key feature of the git and github. You can use git bash to work with branches.
 - To create a new branch
 > git branch <branch name>
 
 - To switch to another branch
 > git checkout <branch name>
 
 - To delete a branch
 > git branch -d <branch name>
 
 ## Git Status
 > git status
 
 ## Git Make a SSH key
 Follow the 1 & 2 links to generate and add SSH key to your github account
 
 1. https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/
 2. https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account
 
