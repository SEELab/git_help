Git Branches
============

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
