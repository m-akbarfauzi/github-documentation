# Upload Repository From CLI


## 1. Open Terminal

You can use github CLI or cmd(command promt) adn run as Administrator

## 2. Login to GitHub CLI

## 3. Create New Repository

```
gh repo create m-akbarfauzi/repo-new
```
## 3. Initialize

```
git init -b main
```

Description:

Git init : untuk membuat repository pada file lokal yang nantinya ada folder .git

## 4. Adding repository

```
git add .
```
## 5. Commit the repository

```
git commit -m "this is my first repository"
```
## 6. Adding remote on GitHub

```
git remote add origin https://github.com/{user-or-organization}/repo-new.git
```
## 7. Upload your repo
```
git push -u origin main
```
