# DAY TWO TASK

_**Question1. How git workflow works?**_ 

> Git workflow has four fundamental stage-

1. Workspace: working directory

2. Index(stage) :It is used as staging area between working directory and your repository

3. Local repository is the one on which we will make local changes, generally Local repository is on our computer. 

4. Remote repository is one of the server. 


_**Question2. What are the different stages of a git project as commit, add?**_ 

> 1.Modified: you can make changes to your copy of the project without disturbing the original code. 

2.staged:Staging area is the place where files has been added but changes have not been commited. 

3.commit: The changes has been committed. 


_**Question3. Q3>Is it possible to do a git commit before git add. If you have made any changes? Explain why?**_
> -> **No** it's not possible to do a git commit before git add, as the file must be added to the index(staging area) and then it must be commited. 

_**Question4. Why is git diff used?**_ 
->It is used to find the difference between the changes made on a file. 

_**Question5. Can we leave commit message as blank?**_ 
> ->yes we can leave the commit message as blank
By using the command
git commit -a --allow-empty -message -m ""

My github repo link is:
https://github.com/nanakjaswani/weather_accuracy?files=1


# Day 3 Task:
_**Q. 1) What is meant by the term fork and clone?**_
> Ans: Fork -Creating a fork is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit Pull Requests to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.

Clone - clone is same as what the word has in the literary terms, making a copy of the files present in the cloud on github server to your local machine.

_**Q.2) What are branches in github?**_
> Ans: Git branch is a feature in git used for separating a feature or part of code from you your master in order not to mess something in your main code like suppose you have a website as a project in git and you want to add a new feature to it so you do it by creating a new branch for it so your main code remain the same as it and once you complete it then you merge it with your master. 

_**Q.3) What is PR?**_
> Ans: A pull request is submitted when you’ve worked on some code from a particular branch and want to inform the others of the changes you’ve made.

_**Q.4) Can we delete the master branch if not why?**_ 
> Ans: Yes, we can delete the master branch by changing our github repo default branch.

_**Q.5)How can we delete a branch?**_
> Ans: We can delete a branch by using *-d command*:

PR link:
https://github.com/nanakjaswani/gitseries/tree/master/Nanak

https://github.com/deepak2431/gitseries/pull/35