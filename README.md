# github_config

## 1、create a new repository on the command line

```
echo "# github_config" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sameion/github_config.git
git push -u origin main
```

### 2、push an existing repository from the command line

```
git remote add origin https://github.com/sameion/github_config.git
git branch -M main
git push -u origin main
```
