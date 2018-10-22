# GitHub Tutorial

_by Wilson Zhang_

---
## Git vs. GitHub
**Git:** a version control that help keep "snapshots" of code
* the tool that you could use
* ***we do not need Github for Git to work***  

**GitHub:** stores your code in a cloud (a network of servers that is hosted on the internet)
* the service for project that uses Git
* ***we need Git to use Github***

---
## Initial Setup
#### **Create a Github account**
1. First go into the home Github website [(click here for the link)](https://www.github.com)
2. Then click sign up near the top right

---
## Repository Setup
When you first create a directory that are important steps to take before you can save your code:  


---
## Workflow & Commands
#### Important Commands
`git status`
* the best tool to solve any (*most*) problems since it provide hints to fix a problem
* it is used to see the state of your file(s)  

`git add`
* it is a command to add a file to the "staging area" which lets the computer know your change
* gets the files ready for a commit(save)

`git commit`
* a command to save your changes 
* *it needs your file to be add to the "staging area"*

`git push -u origin master`
* git push - is to send your commits to github
* -u - means upstream, it saves which github repository it is sending to 
    * *without it you have to type the whole `git psuh -u origin master` again*

---
## Rolling Back Changes