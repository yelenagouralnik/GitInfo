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

## get rid of the branch work
1. Created new branch
2. Entered some stuff
3. add to stage and commit changes
4. switch back to the previous brench
5. file in editor changes based on a branch 

## git diff between two branches
    ```
    git diff <branch1> <branch2>
    git diff mater ticket1
    ```
    