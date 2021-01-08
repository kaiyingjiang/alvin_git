# Tutorial for Git Operation
1. Always remember to `git pull` and `git fetch` before anything else
2. Procedure for uploading things:
```sh
git add -u #this only adds already added (now modified) file
OR
git add <xxx> # add specific file xxx to git

git commit -m "say something meaningful here"
git push origin <branch_name>
```
3. check status using `git status`

## Branch
1. Create branch using `git checkout -b <branch_name>`
2. Switch to branch using `git checkout <branch_name>`
3. General update: `git fetch` Usually we can also do `git pull origin <branch_name>` instead.
   NOTE: `git pull` = `git fetch` + `git pull origin <current_branch_name>`
4. See all branches `git branch -a`
