
# How We Create Repository With CLI Commnad And Push 

## Install gh command for windows,linux and mac


## {Login With Github} 

```bash
gh auth login
```
Choose GitHub.com

Choose HTTPS

Paste a Personal Access Token

## Create directory

```bash
mkdir <directory naame>
```
```bash
cd <directory name>
```
## {Stage and commit the files}

```bash
git add .
```
```bash
git commit -m "<version-name>"
```
## {Create GitHub Repo & Push It}

## create public directory

```bash
gh repo create my-devops-project --public --source=. --remote=origin --push
```
## For Private Repo

```bash
gh repo create my-devops-project --private --source=. --remote=origin --push
```
## Authors

- [singhnirbhai](https://www.github.com/singhnirbhai)

## How We delete repo

```bash
gh repo delete <name of repo>
```
Fill the reponame for confirmation delete

For Web view used

```bash
gh repo view --web
```
