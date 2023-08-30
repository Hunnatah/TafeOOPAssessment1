# Part 2

### List three major version control for software engineering.SS
* Git
* CVS
* Mercurial

### What are the main advantages to using Git in your software development, and how is it useful for game developers.
* Branching capabilities: This allows developers to create a seprate "area" for each new feature or bugfix while never drectly changing the main branch, allowing for more streamined development.
* Distributed development: This means that everey developer works off of their own local copy of the remote repository rather than a link to the same repo that evereyone else is working off of. This seperation minimizes peoples direct influence on other peoples work, which would frequently cause problems and setback.
* Local repository history: Each local repo has its own commit history, allowing developers to revert local changes if neccessary.

### Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge
Repository: A file documenting any and all changes to the file system of your project/product. They can either be local, an individual copy that is stored on the users device, or remote, the central copy or final product that is stored on a seprate server with everey local repository working out of it.

Pull: The action of copying data and changes from the remote repository to the local one, ensuring that local is up to date with remote

Push: The action of updating the remote repository by copying data and changes over from the local one 

Working Copy: A copy of the project/product that is currently being worked on directly, is accompanied by a local repository

Branch: A separation in the repository to help prevent conflicts caused by multiple simultaneous changes to the same project. Changes in one branch can be merged into another

Merge: The act of pushing changes from one branch to another

### If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.


### Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
* meld
* opendiff
* vimdiff

### In a merged source code file, how does Git let you know there is a conflict?
Git will not allow conflicting diles to be merged. If you try to do so, it will notify you that the process has failed due to a merge coflict and that you need to solve said conflict for the proces to continue

### What are the steps you can take to resolve Git conflicts?
When a merge conflict occurs, users can view the conflicting changes side by side and choose which side to keep while the other one will be discarded.

### What does git revert do, and how can you use it?


### What does git reset do, and how can you use it? 


### What is the difference between git revert and git reset?


### True or False: It is okay to commit broken code to the main branch.
False
### True or False: A commit should only include files that are related to the change you are committing to the repo.
True
### Describe what is DevOps, how is it useful for game developers?


### List what tools can be used with DevOps. Give a brief description of each one. (at least 3)


### What is CI/CD and how can it be used to automate the game development process?

