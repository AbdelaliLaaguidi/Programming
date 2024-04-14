**Git Commands**

**1. Configure Global User Name and Email**

```
git config --global user.name "[firstname lastname]"
git config --global user.email "[valid-email]"
```

**2. Set Default Branch**

```
git config --global init.defaultBranch main
```

**3. Get Help for a Command**

```
git help COMMAND
git COMMAND -h
```

**4. Repository Operations**

- Clone a Repository:

```
git clone REPOSITORY URL
```

- Initialize a Repository:

```
git init
```

**5. Stage Changes**

- Add specific file:

```
git add [file]
```

- Add all changes:

```
git add .
git add --all
git add -A
```

- Remove from staging area:

```
git reset
git remove --staged
git rm --cached <file>
```

**6. File Operations**

- Remove a file:

```
git rm FILENAME
```

- Move or rename a file:

```
git mv [existing-path] [new-path]
```

- Restore changes in a file:

```
git restore [file-name]
```

**7. Check Status**

```
git status
```

**8. View Changes**

```
git diff
```

**9. View Commit History**

```
git log
git log --oneline
git log -p
```

**10. Undo Changes**

- Reset to a specific commit:

```
git reset [log-id]
```

**11. Branch Operations**

- List all branches:

```
git branch
```

- Create a new branch:

```
git branch [branch-name]
```

- Switch to a branch:

```
git switch [branch-name]
```

- Merge a branch:

```
git merge -m "message" [branch-name]
```

- Delete a branch:

```
git branch -d [branch-name]
```

- Create and switch to a new branch:

```
git switch -c [branch-name]
```

**12. Remote Operations**

- Add a remote repository:

```
git remote add origin https://github.com/AbdelaliLaaguidi/Git.git
```

- Rename the default branch:

```
git branch -M main
```

- Push changes to a remote repository:

```
git push -u origin main
git push --all
```

- Fetch changes from a remote repository:

```
git fetch
git merge
git pull
```

---
