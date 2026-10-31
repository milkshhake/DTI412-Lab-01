# Git Command Cheat Sheet

## 1. Git Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
git config --list
```

## 2. Repository Commands
```bash
git init
git clone repository-url
git status
```

## 3. Basic Git Commands
```bash
git add .
git add filename
git commit -m "Commit message"
git push origin main
git pull origin main
```

## 4. Branch Commands
```bash
git branch
git branch new-branch
git checkout branch-name
git switch branch-name
git merge branch-name
```

## 5. History Commands
```bash
git log
git log --oneline
git diff
```

## 6. Remote Repository Commands
```bash
git remote -v
git remote add origin repository-url
git push -u origin main
```

## 7. Useful Git Commands
```bash
git restore filename
git rm filename
git mv old-name new-name
git --version
```