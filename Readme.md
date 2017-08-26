# Digital Logic Lab Fall 2017
# Lab 01
-----------------------------------------------------------

## Description

In this lab, we will get ourselves familiar with git and github classroom tools.
All the details will be discussed in the lab session.

Some useful resources:
  - [Git manual](https://git-scm.com/doc)
  - [Git cheatsheet](http://ndpsoftware.com/git-cheatsheet.html)
  - [Git koans](http://stevelosh.com/blog/2013/04/git-koans/)
  - [Github markdown](https://guides.github.com/features/mastering-markdown/)
  
-----------------------------------------------------------

## Basic Bash Commands

  - Create directory
  ```Shell
  mkdir <dirname>
  ```

  - Show current location
  ```Shell
  pwd
  ```

  - Change directory
  ```Shell
  cd
  cd <dirname>
  cd ..
  cd -
  ```
  
  - Show all the files in current directory
  ```Shell
  ls
  ls -l
  ls -plsha
  ```
  
### Change 

## Git

![git](pics/git.2.14.1.png)

## Git commands
  - Obtaining the repository
  ```Bash
  git clone '<repository url>'
  ```
  
  - Set User information


  - Checking the status of the repository

  - Adding changes

  - Committing changes to local repository

  - Push local changes to remote

  - Getting update from remote

  - Checking the logs
  ```Bash
  git log
  git log --oneline --graph --decorate=auto --color
  ```

## Assignment

  1. Answer all the question in the comment
  2. All members of the group must commit, i.e. I want to see all the members making meaningful changes

  - what is git? what does it do?
shell```
It is computer program for managing code and sharing files. It helps manage and track changes to your code so you can collaborate with others.
```  
  - why is user information important?

  - what is the difference between https and git url?
shell```
Skipped
```  
  - After you made a change to a file, in order to push that change to the remote repository what the steps you must perform? (List all the steps in order)
shell```
1. git status
2. git add <file name>
3. git commit
4. git pull
5. git push
```
  - After you are informed that there are some changes have been made, what are the steps you must follow in order get those changes? (List all the steps in order)
