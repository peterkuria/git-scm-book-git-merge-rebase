# Git merge vs rebase

m1
m2

m3
To merge the changes on the feature branch and the master branch
$ git merge featureBranchName

$ git merge  --squash branch1
The above summarizes all the different commits all the changes in the feature branch in the last commit then
merges the last commit with the latest commit in the master branch

$ git commit -m 'feature branch1 and master merge'

$ git log
$ git status
