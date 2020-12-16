# Git basics

### Basics
<code>git --version</code> - check git version<br> 
<code>git --help</code> - get all git commands<br>
<code>git init</code> - init new repository<br>
<code>git status</code> - check repository status<br>
<code>git add <filename></code> - add file to git tracking<br>
<code>git rm --cached <filename></code> - remove file from git tracking<br>
<code>git add .</code> - add all untracked files<br>
<code>git add *</code> - add all untracked files<br>
<code>git commit -m “Commit description”</code> - commit tracked changes<br>
<br>
### Branches
<code>git branch</code> - view all branches<br>
<code>git branch <branch name></code> - create branch<br>
<code>git branch -D <branch name></code> - remove branch<br>
<code>git checkout <branch name></code> - switch to other branch<br>
<code>git checkout -b <branch name></code> - create new branch and switch to it<br>
<code>git merge <branch name></code> - merge current branch (git branch to check) with a <branch name> branch<br>
<br>
### Connect local repo with remote (Github example)
**config git**
<br>
<code>git config --global user.name</code> - change git user name<br>
<code>git config --global user.email</code> - change git user email<br>
…
<br>
**connect remote repo with local**<br>
<code>git remote add origin <path to remote repo></code><br>
**push local repo changes to remote repo**<br>
<code>git push -u origin master</code>
**next to publish local changes to remote**<br>
<code>git push</code><br><br>

### Clone repository from remote to local<br>
<code>git clone "path to repository" </code>

### Get latest code updates from remote repo (update local repo)<br>
<code>git pull</code>
