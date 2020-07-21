# git-cheat-sheet
A cheat sheet of the git commands I use


## Clone a Repository
Clones a git repository from a source such as github to your local device.
```git
git clone <reopository>
```

## Pull changes from origin
Compares the differences between your local repo and the origin, then pulls the changes to the local repo.
```git
git pull
```

## Check the difference between origin and local
Lists all modified files and their changes from the original.
```git
git diff
```

## Check the difference between a file on origin and local
Lists the changes of the file compared to the original
```git
git diff <file name>
```

## Check the status of tracked and untracked files
Tells you whether a file is tracked or not as well as if they've been modified or not.
```git
git status
```

## Track a file
Track a file by adding it to the commit
```git
git add <file name>
```

## Remove a file or piece of code from commit
```git
git reset <file name>
```

## Commit a specific code block from feil
```git
git add -p <file name>
```

## Reset a file to original state
```git
git reset <file name>
git checkout <file name>
```










