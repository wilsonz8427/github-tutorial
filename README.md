# GitHub Tutorial

_by Wilson Zhang_  

##### Note: This tutorial is mainly for people who uses Cloud 9 IDE 

---
## Git vs. GitHub
**Git:** a version control that help keep "snapshots" of code
* the tool that you could use
* ***we do not need Github for Git to work***  

**GitHub:** stores your code in a cloud (a network of servers that is hosted on the internet)
* the service for project that uses Git
* ***we need Git to use Github***

Git is only a tool for the users to use when programming while github is a cloud that allows the users to store their code.

---
## Initial Setup
#### **Create a Github account**
1. First go into the home Github website [(click here for the link)](https://www.github.com)
2. Then click sign up near the top right
3. Then please enter a username that you will use(use your hstat email but without @hstat.org)
4. Then type in your email that you want to use(hstat email)
5. Make sure to verify account and then click "Create an account"
6. Then choose your plan(students please choose FREE) and click "Continue"
    * The Checkboxes is optional
7. Next answer the questions and press Submit
8. When it is loaded it is COMPLETED!
---
## Repository Setup
#### On the Cloud 9
**Please refer to *Workflow & Commands* if you need the definitions and usage of a command**  

When you first create a directory there are important steps to take before you can save your code:  
1. You should always cd(move) into the directory
2. Use `git init` to allow git to start saving your changes
3. After you have made some changes to a file you can do `git add`
4. Finally, right after `git add` you can do `git commit -m ""` to save you changes

#### New Repository on Github
When you are sign in you should see your profile picture on the top right
1. Click the profile picture and click "your repository"
2. Next click the Green Button on the right side that says "NEW" 
3. Type in a name for your repository. Name your repository the same as you have name your directory in your IDE(or local)
4. You may leave the other settings alone. If you wish, you may change it

---
## Workflow & Commands
#### Important Commands
`git status`
* the best tool to solve any (*most*) problems since it provide hints to fix a problem
* it is used to see the state of your file(s)  

`git init`
* To **initilize** the directory and set up the tool for git

`git add`
* it is a command to add a file to the "staging area" which lets the computer know your change
* gets the files ready for a commit(save)

`git commit -m ""`
* a command to save your changes 
* `-m ""` allows you to add your own message to your commit(save) you put your message in between ""
* *it needs your file to be add to the "staging area"*

`git push -u origin master`
* `git push` - is to send your commits to github
* `-u` - means upstream, it saves which github repository it is sending to so next time you are pushing your saves you can just write `git push` and do not need the rest
    * *without it you have to type the whole `git push -u origin master` again*
* `origin` - the remote that we are pushing to
* `master` - the "main" branch that we are pushing to

---
## Rolling Back Changes
