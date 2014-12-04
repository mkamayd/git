#Branch and merge locally
###Create a new branch
```
git branch new-branch

```
###Move to that branch
```
git checkout new-branch

```
###Do some work 
```
//some work
git add *.*
git commit -m "some work"

```
###Go back to main branch and merge. 
```
git checkout master
git merge new-branch
//you are done :)
git log

```
### To know were you are.
```
git branch

```

[back](https://github.com/mkamayd/git)