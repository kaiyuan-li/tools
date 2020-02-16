delete branch locally

git branch -d <branch_name>

delete both locally and remotely using

git push origin --delete <branch_name>

prune obsolete branches

git branch -r

revert uncommited changes:
git checkout -- <fiilepath>
  
sync branch with master:
git checkout master
git pull
git checkout <branch>
git merge master
