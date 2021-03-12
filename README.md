# Basic git-commands
commands for git (introduction to basic Git commands)

### 1. Clone a gitlab project (git clone)
- Create a working copy of a local repository:
    
        git clone /path/to/repository
       
- For a remote server, use:
    
       git clone username@host:/path/to/repository

### 2. Create an empty Git repository or reinitialize an existing one
- Create an empty Git repository or reinitialize an existing one
      
      git init
     
     
### 3. once project is cloned successfully at the specific location for example `C:\Users\anurag`
- Chnage the directory to work on

      cd cloned/repository/folder name
e.g.

    C:\Users\anurag\cd git-commands
### 4. after finishing your changes, add all changed files to index
- this would add untracked files that aren't being ignored
        
      git add .
- only stages changes (including deletions) to already tracked files.
   
      git add -u
- add one or more files to staging(index)

      git add  <filename> 
      git add *
   
### 5. check the status of the file that added
- using this command we can check that files are added or not, the filed that added will be shown in green letters
     
      git status
### 6. Create a new branch and switch to it
    git checkout -b <branchname>

### 7. Switch from one branch to another
    git checkout <branchname>
### 8. List all the branches in repository, and also to find out which brnach we are currently in
    git branch
### 9. Delete the branch
    git branch -d <branchname>
### 10. 
    
