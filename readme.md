Intro to git for window. 

Github: version control and source code management system.

Git for window: https://git-scm.com/download/win

sublime merge: https://www.sublimemerge.com/

useful bash command

- `cd /c` navigate to disk C
- `cs ~` navigate to root directory
- `pwd` to show current location
- `ls -lA` list all hidden and non hidden files/fodler



## Create a repository(project):

- navigate to current project folder using `cd` command. (misc cmd: `ls` list all folders and files 
- go to GitHub. create a new repository
- `git init` inside project to make project become a git project.


## To make a  commit using command line.
- run `git status`
- `git add {FILENAME1} {FILENAME2}` ex: `git add readme.md index.html`
- `git commit -m "{COMMIT MESSAGE}"`


## Bind local git project with github.
- `git remote add orign {PROJECT LINK}` ex: `git remote add origin https://github.com/datduyng/intro-to-github`. bind local git project with github project. 


## update changes from local to remote repository on github
- `git push origin master`