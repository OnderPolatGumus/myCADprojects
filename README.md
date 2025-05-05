# Git Pull & Push Tutorial

This guide explains how to **pull** (download) and **push** (upload) changes to a GitHub repository using Git Bash or any terminal with Git installed.

---

## 📥 Pulling Changes

### 1. Clone the repository (if you haven't yet)
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Pull the latest changes from the remote
```bash
git pull origin main
```
---

## 📤 Pushing Changes

### 1. Make your changes in the project directory

### 2. Stage the changes
```bash
git add .
```

### 3. Commit the changes
```bash
git commit -m "Describe what you changed"
```

### 4. Push to GitHub
```bash
git push origin main
```
> Again, replace `main` with your actual branch name.

---

## 🔍 Check Your Git Config

To ensure Git is using your correct identity:
```bash
git config --global user.name
git config --global user.email
```

To set them:
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

---

## ✅ Done!

You have now pulled and pushed changes using Git. Happy coding!
