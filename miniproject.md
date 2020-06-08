
  
### GitFlow workflow

It is a tree-like architecture or a file structure that Git uses, where there is a reporsitory and a working copy of that repository. In order to move files between the repository and a working copy, 
 

## Repository:
After Git has been installed and configured, next is to put Git in the appropriate condition to start its operation. That is asking Git to start tracking changes in a particular project. We need to however decide where to put the project for Git to start tracking. This location is called a Repository. The repository can be a new folder created in a Windows directory on a Desktop.

The folder can be accessed via the command line by changing in to the windows directory in which that folder was created. Once in the root of the folder via the command Line, entering - Git init will tell Git to get everything ready to start doing its tracking.

A repository can also be created in the User Interface from the home screen after signing into your account, and then selecting 'New' or the 'Plus' sign (+) on the top right corner of the home page. See file attachment called 'Create a new repository.

![Screenshot added on creating a new repository](https://raw.githubusercontent.com/pyruskimo/LarryTaiyeImages/master/TestImage1.PNG)


 
## Clone
A clone is a copy or the act of making a copy of a repository, for example, a copy of the the master branch. When a clone is made, files can be edited and Git will track the different changes made. The repository that was cloned is still connected to the remote version such that that changes that were made locally can be pushed to the remote to keep them synced.

## Branch:
A branch represents an independent line of development. It is thought of as a way to request a brand new working directory, staging area, and project history. New commits are recorded in the history for the current branch, which results in a fork in the history of the project.
Getting the most out of Git will mean using branches often and effectively. Branches are easy to create, work with, delete and allow testing of different ideas. Assuming working on a project, and suddenly an idea comes to mind. Though uncertain if the new idea will work or not, instead of making lots of commit to the master branche and undoing <del>or reverting</del> the changes, a new branch can be created and the new idea test there on. And if the ideas do not work, the branch can be deleted and the master branch would not have been affected by the chnages. However if the idea does workout, those changes can be brought back to the master branch through a process called merging.



## Commit: 
Commit implies telling Git to track the individual change to a file (or set of files). When a commit is made to save a work, Git creates a unique ID called "hash" that allows the keeping of record of the specific changes commited along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made 


 
## Merge
Merging is a way of combining the work from two different branches together where a branch was created to develop a new feature and then combined back in to the main branch or master branch. Git merge will combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches.

**use case**
*Assuming we need to complete a merge following the below screenshot;
![screenshot1](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/Merge1.PNG)

*Invoking this command will merge the specified branch feature into the current branch, we'll assume master. Git will determine the merge algorithm automatically, per below screenshot

![Screenshot2](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/Merge2.PNG)

*![Reference](https://www.atlassian.com/git/tutorials/using-branches/git-merge)

## Checkout
In Git terms, a "checkout" is the act of switching between different versions of a target entity. The git checkout command operates upon three distinct entities: files, commits, and branches. In addition to the definition of "checkout" the phrase "checking out" is commonly used to imply the act of executing the git checkout command. 

## Push
The git push command is used to upload local repository content to a remote repository. Pushing is how commits are transfered from a  local repository on to a remote repository.
- It uses the following command: git push <remote> <branch>
  After a local repository has been modified a push is executed to share the modifications with remote team members.

![Before and after Git push diagram](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/Git%20Push.PNG?raw=true)

*[Reference](https://www.atlassian.com/git/tutorials/syncing/git-push#:~:text=The%20git%20push%20command%20is,repository%20to%20a%20remote%20repo.&text=Remote%20branches%20are%20configured%20using,should%20be%20taken%20when%20pushing.)



## Pull 
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. The git pull command is actually a combination of two other commands, git fetch followed by git merge. In the first stage of operation git pull will execute a git fetch scoped to the local branch that HEAD is pointed at. Once the content is downloaded, git pull will enter a merge workflow. 


## Remote
Remote allows us to collaborate with others. It is responsible for syncing changes. It also records changes made through the git remote command and are used in conjunction with the git fetch, git push, and git pull commands. 


      Remote Add / Remove / Show
Status
Master Branch





- [x] Repository
- [ ] Clone
- [ ] Fork
- [x] Branch
- [x] Commit
- [ ] Merge
- [ ] Checkout
- [x] Push
- [ ] Pull
- [ ] Remote

        Add
        
        Remove
        
        Show
        
- [ ] Status
- [ ] Master branch
