# git reference

### creating a repo

`git init`: starts a new git repo on local machine
      If using create-react-app, then was already done for you.

On github.com, in USERNAME acct: "Create a new repository", name it, comment optionally, then,,,

`git remote add origin https://github.com/USERNAME/REPONAME.git`

### pushing to git:

1. `git add .' : adds all files in current folder, stages the files
2. `git commit -m "comment"` : commits the staged files
3. `git push origin master': push to repo on github.com

### notes

`.gitignore': sets which folders git should ignore
      The `create-react-app` created the .gitignore file.

'git status' : show the status of the local repo

'git checkout -B NAMEOFBRANCH

then 'git branch`
then `git checkout master`

### pulling from git

`git clone ...` : 

make change, then: 'git pull origin master`
