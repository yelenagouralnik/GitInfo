## Oops Scneario
### Start making changes in the master branch

git checkout -b quickfix
git add *

git commit -m "start of changes for quickfix"

git checkout master

### Renaming branches
```
git branch -m <oldbranch> <newbranch>
git branch  -m quickfix longfix
```
### Deleting a branch

```
git branch -d <branchname>
git branch -d longfix
```
You will get an error message if you try to delete a branch that has unmerged commits

