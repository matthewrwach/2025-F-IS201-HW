# GitHub Pages Setup Instructions

## Step 1: Create GitHub Repository

1. Go to GitHub.com and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., "web-dev-portfolio")
5. Make it public (required for free GitHub Pages)
6. Do NOT initialize with README, .gitignore, or license (we already have these)
7. Click "Create repository"

## Step 2: Push Your Code to GitHub

Run these commands in your terminal (from the project directory):

```bash
git add .
git commit -m "Initial commit - Final Web Development Project"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub username and repository name.

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (top menu)
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" as the branch
6. Select "/ (root)" as the folder
7. Click "Save"

## Step 4: Access Your Site

Your site will be available at:
`https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

Note: It may take a few minutes for the site to be available after enabling GitHub Pages.

## Step 5: Verify Everything Works

Check that:
- ✅ All pages load correctly
- ✅ Navigation links work
- ✅ Images display properly
- ✅ YouTube video embeds correctly
- ✅ Tableau visualization loads
- ✅ Web app is playable
- ✅ No broken links or content

## Troubleshooting

- If pages don't load, wait 5-10 minutes and refresh
- Make sure all file paths are relative (not absolute)
- Check that `index.html` is in the root directory
- Verify all CSS and image paths are correct

