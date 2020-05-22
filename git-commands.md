- `git init`<br>
  create a new local GIT repository in the curret directory<br><br>
- `git init [project name]`<br>
  create a new repository within a new directory of the name<br><br>
- `git clone username@host:/path/to/repository`<br>
  copy a repository if it lies on a remote server<br><br>
- `git clone /path/to/repository`<br>
  copy a local repository<br><br>
- `git add <filename>`<br>
  add the file to staging area<br><br>
- `git commit -m"Message to go with the commit"`<br>
  create a snapshot of the chnages and save it to the git directory<br><br>
- `git config --global user.email youremail2example.com`<br>
    to set user-specific configuration values like email, username, file format etc<br><br>
    the above command is used to set up an email<br>
    -global flag tells git to use that email for all local repositories<br><br>
- `git config --local user.email yourmail@example.com`<br>
      to use different mails for different repositories<br><br>
- `git status`<br>
  displays the list of changed files together with te files that are yet to be staged or commited<br><br>
- `git push origin master`<br>
  to send local commits to the master branch of the remore repository<br><br>
- `git add <filename>`<br>
  add the file to staging area<br><br>
- `git checkout -b <branch-name>`<br>
  creates a new branch and switches to it<br><br>
 - `git checkout <branch-name>`<br>
  switches to the mentioned branch<br><br>
 - `git remote -v`<br>
  view all remote repositories <br><br>
 - `git remote add origin <host-or-remoteURL>`<br>
  connect the local repository to a remote server<br><br>
- `git remote rm <name-of-the-repository>`<br>
  delete a connection to a specified remote repository<br><br>
 - `git branch`<br>
  list all the branches<br><br>
 - `git branch -d <branch-name>`<br>
  delete branch<br><br>
  - `git pull`<br>
  merges all the changes present in the remote repository to thelocal working directory<br><br>
 - `git merge <branch-name>`<br>
  merge a branch into the active one<br><br>
 - `git diff --base <file-name>`<br>
  view conflicts against the base file<br><br>
  - `git diff <source-branch> <target-branch>`<br>
  view conflict between branches<br><br>
  - `git diff`<br>
  list down all present conflicts<br><br>
   - `git tag <insert-commitID-here>`<br>
  mark specific commits <br><br>
 - `git log`<br>
  see repository history by listing commit details<br><br>
 - `git reset --hard HEAD`<br>
  reset the index and working directory to the last git commit's state<br><br>
 - `git rm filename.txt`<br>
  remove files from index and working directory<br><br>
 - `git fetch origin`<br>
  fetch all objects from the remote repository that doesn't currently reside in the local working directory<br><br>
 
 Read [Git cheat sheet](https://www.hostinger.in/tutorials/basic-git-commands) for more
