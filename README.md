# Review notes for Git Bash

## Git is a version control system for tracking changes in computer files.

#### Initialize a local git repository, creates a .git folder
`$ git init`

#### Add file(s) to index  (to be committed)
`$ git add <filename>`
#### Add all files to index
`$ git add .`

#### To discard changes in the directory
`$ git restore <file>`

#### Remove file(s) from index (not to be committed)
`$ git rm --cached <filename>`

#### Check status of working tree
`$ git status`

#### Commit changes in index
`$ git commit`

#### Commit changes without using an editor for the comment
`$ git commit -m "comment"`

#### Push to remote repository
`$ git push -u origin master`
#####another way:
`$ git push -f origin master`

#### Pull latest changes from remote repository
`$ git pull`

#### Clone repository into a new directory
`$ git clone <url>`

#### Create a new branch
`$ git branch <branch_name>`

#### Merge branches to master
`$ git merge <branch_name>`

#### Go to different branch
`$ git checkout <branch_name>`

#### Create a gitignore file
`$ touch .gitignore`

#### Remove files/folder with gitignore that are already in the repository
`$ git rm -rf --cached .`
`$ git add .`