This is the README. My first one, lets see what we create.
ദ്ദി(ᵔᗜᵔ)
૮₍ ˶ᵔ ᵕ ᵔ˶ ₎ა
₍^. .^₎Ⳋ

Creating a new repo:
git init <- initializing a git repository
Create repo on github
git remote add origin <github http url>
to test run git remote -v - shows if remote repository is connected
How to create / push commits:
git add . - means git add everything, all saved changes
git commit -m "Commit message here"
git push origin main/master or git push origin main/master -u
*** If you use -u upstream flag, all subsequent/further commits you use git push instead of git push origin main

Branching your repo:
git branch <name of new branch> - create a new branch
git checkout to see what branch we are on
git checkout <name of branch> - to switch to different branch
when in alternative branch all changes are saved/commited only to that branch
*** DO NOT MAKE CHANGES TO BOTH BRANCHES ***

Git Merging:
Merging is the process of combining a secondary branch with the main/master branch
Switch to branch you want to merge into (usually main branch)
git merge <name of branch to merge> - combines secondary branch into main
Git Clone:
In terminal, navigate to folder you want to clone code in to.
Run command, git clone <https url from github here> opt_new_name_for_folder
Git Pull:
In terminal, directory should be the repo you want to update
Run command, git pull