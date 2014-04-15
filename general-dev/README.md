# General development tips and tricks
* [Mac set up from NPR](http://blog.apps.npr.org/2013/06/06/how-to-setup-a-developers-environment.html)
* [Software installations](https://github.com/eklucas/NICAR_install)

###Common GitHub commands

####Creating a repo
```bash
mkdir directory_name

git init

touch README.md

git add README.md

git commit -m 'first commit'

git remote add origin https://github.com/username/directory_name.git

git push origin master
```

####Basic commands
To add new files to the repository or add changed files to staged area:
```
$ git add <files>
```
Add all files in a directory and its subdirectories
```
$ git add .
```
To commit them:
```
$ git commit
```
To commit unstaged but changed files:
```
$ git commit -a
```
This will ask for a commit message via VIM. Press "Esc", then ":" "w" "q" (w for write and q for quit).

To push to a repository (say origin):
```
$ git push origin
```
To push only one of your branches (say master):
```
$ git push origin master
```
To fetch the contents of another repository (say origin):
```
$ git fetch origin
```
To fetch only one of the branches (say master):
```
$ git fetch origin master
```
To merge a branch with the current branch (say other_branch):
```
$ git merge other_branch
```
Note that origin/master is the name of the branch you fetched in the previous step from origin. Therefore, updating your master branch from origin is done by:
```
$ git fetch origin master
$ git merge origin/master
```
[SOURCE](http://stackoverflow.com/questions/11019839/how-to-use-github-using-terminal-commands)

###Merging message
1 press "i"

2 write your merge method

3 press "esc"

4 write ":wq" then press enter

###Create .gitignore file
[Useful instructions for creating gitignore file](http://www.gpickin.com/index.cfm/blog/git-for-dummies-using-gitignore-files-to-exclude-certain-files-and-folders)

###Github markdown

[SOURCE](https://help.github.com/articles/markdown-basics)

###Github basics
* [Github for beginners](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1#awesm=~oxo1ZxMiZHjClD)

