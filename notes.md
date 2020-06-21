***File management in repo:***
1. "hello.py" gets pushed to remote repo
2. "notes.md" gets ignored in any adds and commits
3. "README.md" recommended by remote repo - its gets pushed
4. "/dir1" gets ignored in any adds and commits

**Git commands for local repos:**
$ git                           *Displays usage and common Git commands*
$ git --version                 *Displays version of Git*         
$ git init                      *Initialize local Git repository*
$ git config --global           *Configure user name and email (GitHub)*
$ git add <file>                *Add file(s) to index/stage*
$ git add *.py                  *Add any .py files to the index/stage*
$ git add .                     *Add all files to index/stage*
$ git status                    *Check status of working tree*
$ git restore --staged <file>   *Unstages any files in index/stage*
$ git rm --cached <file>        *Remove changes from index/stage*
$ git rm -f <file>              *Force remove from repo even if staged*  
$ git commit -m <message>       *Commit changes in index/stage*
$ git commits                   *Goes to commit window for messaging (i to INSERT, Esc and :wq to QUIT)*
**Git commands for remote repo:**
$ git push                      *Push to remote repository (GitHub)*
$ git pull                      *Pull latest from remote repository*
$ git clone <repository>        *Copy repository to new local directory*
**CMD commands:**
$ touch                         *Creates new file in current directory*
$ touch .gitignore              *Contains list of files that will be ignored by Git commands*
$ mkdir                         *Creates a new directory/folder*
