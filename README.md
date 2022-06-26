# Set of Git Commands to know

## Update URL for Git Repo
Run to see the current remote.
Update remote URL with set-url
```
git remote -v
git remote set-url origin insert_new_git_url
```

Example
```
git remote set-url origin git@github.com:jsohndata/app-clock.git
```

## Add all but one file
```
git add .
git reset -- insert_file_name
```