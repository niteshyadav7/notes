### GIT COMMONDS

**GIT SETUP**

- git config --global user.name "[name of user]"

# set a name that is identifiable for credit when review version history

- git config --global user.email "[email of user]"

# set an email address that will be associated with each history marker

- git config --global color.ui auto

# set automatic command line coloring for Git for easy reviewing

**GIT INIT**

- git init

# initialize an existing directory as a Git repository

- git clone [URL]

# retrieve an entire repository from a hosted location via URL

**STAGE AND SNAPSHOT**

- git add [file name]

# add a file as it looks now to your next commit (stage)

- git commit -m"[descriptive message]"

# commit your staged content as a new commit snapshot

- git status

# show modified files in working directory, staged for your next commit

- git reset

# unstage a file while retaining the changes in working directory

- git diff

# diff of what is changed but not staged

- git diff --staged

# diff of what is staged but not yet commited
