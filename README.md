# Git_Practice
Git Bash Command Practice
Example : 
git init : To initialize folder as a git folder.
git add < file-name> : To add a file to staging area.
                  Note : The Files which are added to staging area those files are eligible for commit.
git commit -m 'msg' : To commit files which are in staging area to local repo.
git remote add <repo-url> : To add files to remote repository.
                 Note: For first time only we should execute this remote add command.
git push -u origin master : It is used to commit changes from local to remote repo.
git status : To see staged, un-staged & un-tracked files.
Staged : Files are ready to commit.
Un-Staged : Files are not ready to commit.
Un-Tracked : Newly Created files.

git reset : It is used to un-stage a file.
                            syntax : git reset HEAD <file-name>
git checkout : It is used to discard changes in working directory and paste the original file which is on repository.
syntax : git  checkout -- <file-name>
