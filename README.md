# Set of git commands

A brief documentation of useful git commands I found.

## Update git remote URL
- Run to see the current remote.
- Update remote URL with set-url.
```
git remote -v
git remote set-url origin new_git_url
```

## Unstaging 
Use ```git reset``` to unstage/exclude a file( or a directory)

```
git reset . (all files)
git reset -- file_name_or_path
git reset -- directory_name_or_path
```

## Adding additional entries to .gitignore
- Add the entires which needs to be removed in .gitignore
- Unstage the entries. This does not delete it from working directory
```
git rm -r --cached . (all files)
git rm -r --cached file_name_or_path
git rm -r --cached directory_name_or_path
```
