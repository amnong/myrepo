Git Session
===========

- Basic commands
- Commit object and hash
- Branches and tags
- Amend
- Rebase
- Cherry-pick
- Interactive rebase
- Merge
- Push
- Reset


```
git config

git init
git add
git commit [-am]
git status
git log
git branch [-a | -r]
git checkout -b
git push [-u origin $BRANCH]
git diff [--cached]
git tag
git push origin --delete another_branch
git fetch --prune

git reset --hard         : erase all uncommitted changes
git reset --hard <REF>   : erase all uncommitted changes and change HEAD of current branch to point to <REF>
git reset                : drop file from staging (do not change content)
git reset <REF>          : change HEAD of current branch to point to <REF> but keep files as they are right now

git checkout - remove from staging
git checkout - change branch
git checkout - get file from another branch

git log --graph --all --oneline --decorate=full
```

Repo
Staging
Dirty

Git pull:

 - git fetch
 - git merge / git rebase

