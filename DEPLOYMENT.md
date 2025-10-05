# Deployment Guide for Arc Privacy Policy

This guide will walk you through deploying your privacy policy to GitHub Pages.

## 📋 Prerequisites

- GitHub account
- Git installed on your computer
- This `arc-privacy-policy` folder

## 🚀 Step-by-Step Deployment

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. Configure your repository:
   - **Repository name:** `arc-privacy-policy`
   - **Description:** "Privacy Policy for Arc AI Summary App"
   - **Visibility:** ✅ **Public** (required for free GitHub Pages)
   - ❌ Do NOT initialize with README (we already have one)
4. Click **Create repository**

### Step 2: Initialize Git and Push Files

Open terminal in the `arc-privacy-policy` folder and run:

```bash
# Navigate to the folder
cd /Users/deepakchougule/Projects/Arc/arc-privacy-policy

# Initialize Git repository
git init

# Add all files
git add .

# Create first commit
git commit -m "Initial privacy policy for Arc app"

# Add your GitHub repository as remote
# Replace YOUR-USERNAME with your actual GitHub username
git remote add origin https://github.com/YOUR-USERNAME/arc-privacy-policy.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub: `https://github.com/YOUR-USERNAME/arc-privacy-policy`
2. Click **Settings** (gear icon at the top)
3. In the left sidebar, scroll down and click **Pages**
4. Under "Build and deployment":
   - **Source:** Deploy from a branch
   - **Branch:** Select `main` and `/ (root)`
   - Click **Save**

### Step 4: Wait for Deployment

1. Click the **Actions** tab in your repository
2. You'll see a workflow running called "pages build and deployment"
3. Wait for the green checkmark (usually 1-2 minutes)
4. Once complete, go back to Settings → Pages
5. You'll see: **"Your site is live at https://YOUR-USERNAME.github.io/arc-privacy-policy/"**

### Step 5: Verify Your Privacy Policy

1. Click the link or visit: `https://YOUR-USERNAME.github.io/arc-privacy-policy/`
2. Your privacy policy should be displayed with the Cayman theme
3. Verify all sections are visible and properly formatted

## 📝 Your Privacy Policy URL

Once deployed, your privacy policy will be available at:

```
https://YOUR-USERNAME.github.io/arc-privacy-policy/
```

**Save this URL** - you'll need it for:
- Google Play Store listing
- Android app integration
- User inquiries

## 🔄 Making Updates

To update your privacy policy:

```bash
# Edit index.md with your changes
# Then commit and push:

git add index.md
git commit -m "Update privacy policy - [describe changes]"
git push

# GitHub Pages will automatically rebuild (1-2 minutes)
```

**Important:** Always update the "Last Updated" date at the top of `index.md` when making changes.

## ✅ Next Steps

After deployment, you should:

1. ✅ **Test the URL** - Make sure it's accessible
2. ✅ **Update Android app** - Add the privacy policy URL to your app configuration
3. ✅ **Update README.md** - Replace `[your-username]` with your actual GitHub username
4. ✅ **Google Play Store** - Add the privacy policy URL to your app listing
5. ✅ **Bookmark the URL** - Keep it handy for future reference

## 🛠️ Troubleshooting

### "404 Not Found" after deployment

- Wait 5 minutes and try again (initial deployment can be slow)
- Check Settings → Pages to ensure it says "Your site is live"
- Make sure repository is public
- Verify the branch is set to `main` and folder is `/ (root)`

### Theme not showing correctly

- Check that `_config.yml` exists in the repository root
- Verify `theme: jekyll-theme-cayman` is present in `_config.yml`
- Try triggering a rebuild by making a small change and pushing

### Changes not appearing

- Check Actions tab for build errors
- GitHub Pages can take 1-5 minutes to reflect changes
- Hard refresh your browser (Ctrl+F5 or Cmd+Shift+R)

## 📧 Need Help?

If you encounter issues:
1. Check [GitHub Pages documentation](https://docs.github.com/en/pages)
2. Review the Actions tab for error messages
3. Ensure all files are committed and pushed correctly

## 🔒 Security Notes

- Keep the repository **public** (required for free GitHub Pages)
- Do NOT commit sensitive information (API keys, passwords, etc.)
- The privacy policy itself is meant to be public
- This is separate from your main Android app code repository

---

**Estimated Time:** 10-15 minutes for complete deployment

Good luck! 🚀

