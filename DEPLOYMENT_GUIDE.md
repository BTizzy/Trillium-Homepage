# GitHub Deployment Guide

## 🚀 Step-by-Step Instructions to Publish on GitHub

### 1. Create GitHub Repository

1. **Go to GitHub**: Visit [github.com](https://github.com) and sign in
2. **Create New Repository**: Click the "+" icon → "New repository"
3. **Repository Name**: `trillium-homepage`
4. **Description**: "Professional website for Trillium Hiring Services - Strategic HR & Talent Acquisition"
5. **Settings**: 
   - ✅ Public (so it can be viewed by others)
   - ❌ Don't initialize with README (we already have one)
6. **Click**: "Create repository"

### 2. Connect Your Local Code to GitHub

After creating the repository, GitHub will show you commands. Use these:

```bash
cd "/Users/ryanbartell/Downloads/trillium-homepage"

# Add GitHub as remote repository (ALREADY DONE!)
git remote add origin https://github.com/Btizzy/trillium-homepage.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

**Your GitHub username: Btizzy** ✅

### 3. Enable GitHub Pages (Free Hosting)

1. **Go to your repository** on GitHub
2. **Click "Settings"** tab
3. **Scroll to "Pages"** in left sidebar
4. **Source**: Select "Deploy from a branch"
5. **Branch**: Select "main" and "/ (root)"
6. **Click "Save"**

🎉 **Your site will be live at**: `https://btizzy.github.io/trillium-homepage`

### 4. Alternative Commands (if needed)

If you encounter issues, try these commands:

```bash
# Check current status
git status

# Check remote connections
git remote -v

# If you need to reconfigure
git remote set-url origin https://github.com/Btizzy/trillium-homepage.git
```

## 📁 What's Included in Your Repository

- `index.html` - Main website file
- `styles.css` - All styling (1494+ lines of CSS)
- `script.js` - JavaScript functionality
- `README.md` - Professional documentation
- `.gitignore` - Git ignore file

## 🌐 After Publishing

Your website will be available at two locations:
1. **GitHub Repository**: For code viewing and collaboration
2. **GitHub Pages**: For live website viewing (if enabled)

## 🔧 Making Updates

To update your site:
1. Edit files locally
2. Run: `git add .`
3. Run: `git commit -m "Description of changes"`
4. Run: `git push`

Changes will appear on GitHub immediately and on GitHub Pages within a few minutes.

---

**Ready to go live!** 🚀