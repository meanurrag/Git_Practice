# Git_Practice
Git Bash Command Practice<br />
Example : <br />
git init : To initialize folder as a git folder.<br />
git add < file-name> : To add a file to staging area.<br />
                  Note : The Files which are added to staging area those files are eligible for commit.<br />
git commit -m 'msg' : To commit files which are in staging area to local repo.<br />
git remote add <repo-url> : To add files to remote repository.<br />
                 Note: For first time only we should execute this remote add command.<br />
git push -u origin master : It is used to commit changes from local to remote repo.<br />
git status : To see staged, un-staged & un-tracked files.<br />
Staged : Files are ready to commit.<br />
Un-Staged : Files are not ready to commit.<br />
Un-Tracked : Newly Created files.<br />
<br />
git reset : It is used to un-stage a file.<br />
                            syntax : git reset HEAD <file-name><br />
git checkout : It is used to discard changes in working directory and paste the original file which is on repository.<br />
syntax : git  checkout -- <file-name><br />
