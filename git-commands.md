# Key Git Commands

## Configuring Git

git config --global maryann-myers51 "Maryann Myers"
git config --global maryann.myers@gmail.com "maryann.myers@gmail.com"

## Initializing a Repository

git init

##Cloning a Repository

git clone https://github.com/maryann-myers51/repository.git

## Staging and Committing Changes

git add filename
git commit -m "Commit message"

##Viewing History

git log

## Branching
git branch new-brnach
git checkout new-branch

##Merging

git merge branch-name

##Deleting Branches

git branch -d branch-name

##HAndling Merge Conflicts

#Edit conflicted files
git add resolved-file
git commit

$$Stashing

git stash
git stash pop

#Rebasing

git rebase branch-name

##Cherry-Picking

git cherry-pick commit-hash
