# Git Cheatsheet

### adding option to push to multiple repositories
```
git remote set-url --add --push origin YOUR-GIT-SSH-URL
```

### renaming local master to main
```
git branch -m master main
git push -u origin main 
git push origin --delete master #login github & change defauly branch & retry command
```

### getting users public keys
```
github.com/USERNAME.keys
github.com/USERNAME.gpg
```

### create a new repository on the command line:
```
git init
git add <FILE_NAMES>
git commit -m "<ENTER_COMMENT_HERE>"
git branch -M main
git remote add origin git@github.com:<USERNAME>/<REPO_NAME>.git
git push -u origin main
```

### push an existing repository from the command line
```
git remote add origin git@github.com:<USERNAME>/<REPO_NAME>.git
git branch -M main
git push -u origin main
```

### Shortcuts:
```
git add . # adds all changed files
git -am # adds all changed files and commits with message
``` 
