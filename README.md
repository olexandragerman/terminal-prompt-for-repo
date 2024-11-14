### terminal-prompt-for-repo
***This repository is for practicing the GitHub Flow for terminal

***Example: Contribute to an existing repository
### dowload ad repositortm on Github  to our machine
### for exemple:
    'git clone git@github.com:olexandragerman/terminal-prompt-for-repo.git'
### chenge in the 'terminal-prompt-for-repo' directory
    'cd terminal-prompt-for-repo'
### create new branch to store any chenges
    'git branch  prompt-for-repo'
### switch to that branch 
    'git checkout prompt-for-repo'
### make chenges, for exemple  edit 'file1.md'  'file2.md' and using editor
### stange the changed files
    'git add file1.md file2.md'
### take a snapshot of the staging area (anything that's been added)
    'git commit -m "this is my repo"
### push changes to github
    'git push --set-upstream origin prompt-for-repo'


** Example: Start a new repository and publish it to GitHub
### create a new directory
   'git init terminal-prompt-for-repo'
### chenge into the 'terminal-prompt-for-repo'
   'cd terminal-prompt-for-repo'
### create the first file in the projeck
   'touch README.md'
### git isn't now about this file
    'git add README.md'
### take a snapshot of the staging area 
    ' git commit -m 'add README.md  to initial commit'
### provide the  path for the reposetory you created on github
    'git remote add origin git@github.com:olexandragerman/terminal-prompt-for-repo.git'
### push changes to github 
    ' git push --set-upstream origin main'
