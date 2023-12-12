## Git basics session documentation

### Some Basic GIT commands:
Pull changes request:
`git pull origin master`

Partial Commit:
`git commit -m "comment" /file1 /file2`

Commit all staged files:
`git commit -am "comments"`

Alternate of above commit command:
```
git add .
git commit -m "comments"
```

Store your git credentials in local repo:
`git config credential.helper store`
(provide your credentials only once while any pull or push request, it will be cached/stored in you repo.)

Uncommit you last commit on local repo
`git reset --soft HEAD^`

Unstaged staged files
`git reset`

check remote origin URL/Source:
`git remove -v`

Update/Change Remote URL:
`git remote set-url origin https://github.com/repo/name.git`

List all branches:
`git branch`

create a new branch on the local repo:
`git checkout -b [branch-name]`

Merge another branch into your current branch:
`git merge [another-branch-name]`

Delete a branch (not current):
`git branch -d [branch-name]`

Git pull/push from/to a particular branch
`git pull/push origin [branch-name]`
