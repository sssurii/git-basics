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

check remove origin URL/Source:
`git remove -v`

Update/Change Remote URL:
`git remote set-url origin https://github.com/repo/name.git`
