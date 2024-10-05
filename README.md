# web-development
This repository is all about what i learned in the journey of becoming web developer
<br>
Author is sandeep kashyap07


<!-- here are some commands of git  -->

<!-- 
1)   clone - we can clone or copy any repository from github by commanding
" git clone  (link of the repository)


2)  cd(change directory) means we want to go inside that repository or the folder
 " cd web-development" by doing this we will inside the web-develpoment folder

 (cd ..  is used to one step back in the directory)

 3) clear - > tp clear the command in the terminal

4) ls -> will show all the files inside that respository

5) ls -a -> it will show the hidden files in the repository

6) status -> it will show the status of the respository means is any there changes done in the respositry 
" git status"

7) add -> adds new or changed files in your working directory to the git staging area
"git add (file name)"
or
"git add . " to add all the files and their changes in the folder

commit - > it is the record of the changes it s like final submission button

"git commit -m " write any thing regarding the changes "

even we commit the changes theh changes will not happen on our original github repository  untill we push them

8) push - > upload local repo content to remove repo
 " git push origin main"
 
 with the push it will update the origin repo with the changes we made in the clone repo

.......................................................................

9) init - > used to create a new git repo
"git init"


10) mkdir -> is used to create a new folder 
"mkdir filname"


11) git remote add origin -> means we want to add or push a file in the 
which is (remote repo) in the github repo(origin ) using its repo link


12) git remote -v  -> to verify the remote repo



_________________________________________________________-
GIT BRANCHES



13) git branch -> to check on which branch we are in the repo


14) git branch -M (rename (mostly (main))) -> to rename branch


15) git checkout <-  branch name  >  -> to jump to another branch

16) git checkout -b <-new branch name >  -> to create a new branch

17) git branch -d <- branch name>  -> to delete the branch
we cannot delete the branch we are standing on

---------------------------------------------------------------

                           WORK FLOW

 create a github repo
         
  clone

  changes 

  add

  commit

  push



______________________________________________________________________

MERGING CODE

git diff <-branch name> -> to compare the content between the branches

git  merge main -> to merge the branch with main branch


PULL COMMAND

git pull origin main
used to fetch and downaload content from a remote repo and immediatly update the local repo to match that content


RESOLVING MERGE CONFLICTS

an event that take place when git is unable to automatically resolve diffreneces in code between two commits




UNDOING CHANGES

case 1 : staged changes 

git reset <-file name>


case 2: commited changes(for one commit)
git reset HEAD~1

case 3 :commited changes (for many commits)
git reset<- commit hash>
git reset --hard <-commit hash>



FORK 
a fork is a new repo thats share code and visiility settings with the original upstream repo"


fork is rough copy
 -->
