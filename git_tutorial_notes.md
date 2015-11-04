First: markdowns https://guides.github.com/features/mastering-markdown/

#Learning git

Git is a version control tool that saves changes to groups of files that you can revert back if needed.

###There are three types of version control:

1. Local version control: saves files to a database on my local computer.
2. Centralized version control: saves changes to a shared server.
3. Distributed version control:  allows many software developers to work on a given project without requiring them to share a common network. 

Complete back ups of everything.

###Files transition between 3 states:
1. Modified files: files that are recently changed.
2. Staged files: files that are marked to be saved.
3. Commited files: files that have been saved.

Git saves all this changes to a directory and then I will be able to modify those files in what is called working directory.

#In the terminal

to configure the editor
```
git config --global core.editor "vim" 
```

To list the configuration of git

```
git config --list
```
Help

```
git help
```

for specific help

```
git help add // press q to quit all the info
```

To show everything that is inside the directory
```
ls
```
**Ignore files**

to ignore files, in the file you type:
*myFile.gitignore*
[git ignore](https://github.com/github/gitignore)

###Git commands

command | what it does
-----------|-----------
git init | initialize a repository
git status | check the status of a file
git add | start tracking and saving changes to an specific file- to stage
git status | check the status of a file
git commit - m "your message" | to commit a file
git commit -a -m "your message"| to skip the staging and the commit message
git rm | remove a file
git rm -rf | remove a directory
git rm --chached | delete a file from the staging area
git mv | to rename or move a file
git log | shows all the previous commit messages
git log --pretty=oneline | to see git log in one line
git log --pretty=format: 




Then you make a commit on your file and to see what has change you press git diff



