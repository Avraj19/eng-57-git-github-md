# Cheat sheet for Bash Commands

This repo covers the following concepts/ tools:
- Bash
- Git
- Github


link for md file format
'''
https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax
'''

| Commands                       |Description                                            |
|--------------------------------|------------------------------------------------------:|
|pwd                             |Tells you where you are in a directory                 |
|ls                              |Show what in directory, does not show hidden files     |
|ls -a                           |Show everything in directory, including hidden files   |
|cd <name of directory>          |Changes location of directory                          |
|cd ..                           |To go back one directory                               |
|cd ~                            |Takes you to home directory                            |
|touch <name of file>            |Creates a file                                         |
|mkdir <name of folder>          |Creates a folder                                       |
|rm <name of file or folder>     |Removes the file or folder, do not remove directories  |
|rm –rf <name of file or folder> |This removes files or folders by force                 |


# Cheat sheet for git

git command

1. git init --> this command add a .git folder to that folder, this creates a timeline version control.

2. git add . --> add to master branch on your computer

3. git commit -m --> commits branch to git github

4. git log --> lets you look at timeline

5. git status --> lets you check that status of branch

6. git checkout <commit number> --> changes to that state to that point of save

7. git remote add origin https://github.com/Avraj19/<name-of-file>.git --> this links the branch on your computer with a branch on a repo

8. git push origin master --> this pushes the committed branch to github master 
