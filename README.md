# GitHub CLI Commands
```
gh auth login
```
- login to your github
```
gh config set protocol ssh
```
- sets the default protocol to ssh
- Can also be set to https
```
gh repo clone username/repo_name
```
- Any Public Repo can be cloned
- clones the repo to your account and gives an option to add a local folder aswell
```
gh repo fork
```
- Go inside the cloned repo and run this command to fork it into your account
- It also changes the origin to the forked repo and adds the original repo as an upstream
```
gh repo fork username/repo_name
```
- forks the repo directly into your account and asks if you need a clone locally

```
gh issue create
```
- Asks for Title, body and creates the issue 

```
gh issue create --title "name" --body "description" --lable ", seperated labels"
```
- Creating issues with more flags
```
gh issue list
```
```
gh issue close <number>
```
```
gh issue status
```

- More issue commands


```

```




# Git Commands

## Branches

### List all remote and local branches
```
git branch -a
```
### Checkout a branch
```
git checkout <branch_name>
```
### Create a branch
```
git branch <branch_name>
```
### Create and Checkout branch
```
git checkout -b <branch_name>
```
### Push a branch to remote
```
git push origin -u <branch_name>
```
### Delete local branch
```
git branch -d <branch_name>
```
### Delete remote branch
```
git push origin --delete <branch_name>
```
## Pull Request
- Chekout to the branch which needs to be merged and run
```
gh pr create
```

```
gh pr create -B <Destination_branch_name>
```
### Send a Pull request to the repo we forked from
```
gh pr create -R <username>/<repo_name>
```


