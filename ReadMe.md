## GIT commands:

Local branches should be synced FROM master with below commands:
git branch(green one is current branch)

 
git checkout <yourLocalBranchName>

git fetch origin

git merge origin/master

or git pull origin master //UI: should fetch and merge on current branch

## commiting changes:

git add .
git commit -m "Commit msg"
or git -am "commit message" //to add all and commit in single line
git push
======================================================

git branch: list of branch

git branch feature1

git checkout feature1

do some changes and commit on new branch

git checkout master

git pull

git checkout feature1

git merge master

 
git push

(or git push --set upstream origin feature1 )

raise PR in github

==================

// delete branch locally

git branch -d <localBranchName>


// delete branch remotely

git push origin --delete remoteBranchName

 
Note-Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet.