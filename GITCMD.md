### GIT Comands

**GIT SETUP**

- touch file_name

#### only works on git bash to create a file

- mkdir folder_name

#### to create the folder

- git config --global user.name "[name of user]"

##### set a name that is identifiable for credit when review version history

- git config --global user.email "[email of user]"

##### set an email address that will be associated with each history marker

- git config --global color.ui auto

##### set automatic command line coloring for Git for easy reviewing

**GIT INIT**

- git init

##### initialize an existing directory as a Git repository

- git clone [URL]

##### retrieve an entire repository from a hosted location via URL

**STAGE AND SNAPSHOT**

- git add [file name]

##### add a file as it looks now to your next commit (stage)

- git commit -m"[descriptive message]"

##### commit your staged content as a new commit snapshot

- git status

##### show modified files in working directory, staged for your next commit

- git reset

#### unstage a file while retaining the changes in working directory

- git diff

#### diff of what is changed but not staged

- git diff --staged

#### diff of what is staged but not yet commited

**BRANCH AND MERGE**

- git branch

#### list your branches. a \* will appear next to the currently active branch

- git branch [branch name]

#### create a new branch at the current commit

- git checkout [branch name]

#### switch to another branch and check it out into your working directory

- git merge [branch name]

#### merge the specified branch’s history into the current one

- git log

#### show all commits in the current branch’s history

- git branch --d[branch name]

#### By this cmd you can delete the branch which already exist.

- git diff branchB...branchA

#### show the diff of what is in branchA that is not in branchB

# SOME IMP CMD

- git rm [file name]

#### delete the file from project and stage the removal for commit

- git revert <commit_id>

#### Revert commit changes


- start [file_name]
  
### to open file 

- mv oldName newName

### to rename the file

- rndir [folderName]
  
### to remove folder
