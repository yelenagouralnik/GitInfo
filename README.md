# GitInfo
GitTrainingIngo
```git
git config --global color.ui true
git log --pretty=oneline
git log --pretty=format:"%h %ad- %s [%an]"
git status --short
```
git diff
1. What changes have I staged that are ready to be committed?
2. What changes have I made but not yet staged?
```git
git diff --staged
```
### git log
git log --stage
### commit message rules
https://chris.beams.io/posts/git-commit/
### To stop file from being tracked by git
```
git rm --cached filename
```
http://git-school.github.io/visualizing-git/
### Checking out new branch
 `git checkout -b new_branch`