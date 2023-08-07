### Push data to a new repository
`git init` 

`git add .`

`git commit -m "first commit"`

`git remote add origin http://myrepoutl.git`

`git branch -m main`

`git push -u origin master`

### New branch

`git checkout -b new-branch-name`

#### New branch from a specific branch

First argument, our new branch name ex. "feature-test". Second argument, the branch we create it from ex. "develop".

`git checkout -b new-branch-name target-branch`

### Switch branch

`git checkout branch-name`

### Delete branch on local machine

`git branch -d branch-name`

### Add all files to commit

`git add .`

We also can add specific files
`git add file1 file2 file3`

### Commit changes

`git commit -m "commit message"`

Always add a message to your commit.

### Push changes to remote repository

`git push origin branch-name`

or short version: `git push`



## Use with caution

### Delete a remote branch

`git push origin --delete branch-name`
