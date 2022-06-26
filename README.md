# Set of Git Commands to know

## Update git remote URL
-- Run to see the current remote.
-- Update remote URL with set-url.
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
