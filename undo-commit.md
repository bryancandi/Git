### Move branch back 1 commit, keep your file changes
```
git reset --soft HEAD~1
```
Or to unstage changes as well:
```
git reset --hard HEAD~1
```

Make edits...

### Stage and Recommit
```
git add .
```
Or for specific file:
```
git add filename
```
```
git commit -m "Updated commit message"
```

### Force-push rewritten history
```
git push --force
```
