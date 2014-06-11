git_help
========

Useful links:
Git's basic tutorial = http://git-scm.com/book/en/Git-Basics
*Git Sheet* = http://byte.kde.org/~zrusin/git/git-cheat-sheet-large.png
Help Videos = https://asciinema.org/~MKLau
Cool way to learn git = www.codeschool.com

**Git** = a tool for managing projects, originally software. You can use Git to track changes made to files in your projects.

**Github** = an set of interfaces (on the web and your computer) that facilitate project management via Git. You can access much of the power of Git via Github. 

You should be able to get the jist of Git by using Github. Explore the files in this repository and try changing files. Remember to "commit" (see below) your changes that you make!

*Terminology*
- Repository = a project and associated files from Git 
- Cloning = copying a repository from one computer (usually a server) to another
- Branching = telling Git to keep changes that you make separate from other changes made in a repository, which is useful for creating software versions 

*Basic Workflow with Git and Github*

1. I suggest working in Github first, but if you want to work on your computer you will need to initiate or clone a repository.
2. Checkout the proper branch relevant to your project (see *Branching* below).
3. Make changes to files.
4. Annotate and commit changes (Note: commandline users will need to add changes before committing and then pushing).
5. Push these changes to the server (usually on Github), which will backup and make these changes available.
6. Repeat.

*Branching*
Branching allows users to control how the changes that they make get combined.

A good framework for branching can be found here: http://nvie.com/posts/a-successful-git-branching-model/

*Different Branch Types*
- Master = the main branch that is the stabile version
- Develop = the development version of the package
- Features = branches checked out to add particular things to the package
- Hotfix = a branch to make a sudden change to the package in emergencies

Here is a summary of this method:

1. Coordinate with collaborators to define a goal
2. Create or check-out a "Feature" branch from the "Develop" branch (e.g., MKL or fixplotting)
3. Make the changes you need and consistently add-commit-push these changes with concise commit annotation 
4. Solving issues/bugs that you have can be aided by using the Github Issues
5. These Feature level changes will then be integrated into the development version of the package and eventually the Master for the package will be updated by the development version via merging. 

*Pushing*
This is pretty simple in principle. You want to make your changes available to others, so you need to send your committed changes to a central server, such as Github. This is done automatically on Github.

*Advanced Concepts*
- Forking = cloning a repository without contributing changes back to the original repository, like sympatric evolution you get something new through isolation
- Adding = tells Git to track changes to files
- Committing = groups added changes together with annotation, which combined with adding allows the user to break up tasks
- Pushing = takes committed changes on one computer (i.e., yours) and combines them with changes on another computer (e.g., a server)
- Master = the primary branch of a repository, which you can think of as the "stabile" version of the package that everyone should be using
- Origin = the "other" computer the commits are pushed

If you have specific questions/comments, please add them in the Issues section of this repository: https://github.com/SEELab/git_help/issues.
