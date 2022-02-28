# Learn-git
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
