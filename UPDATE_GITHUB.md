# How to Update GitHub Repository

## Method 1: Git Commands (Terminal)

1. Open PowerShell/Terminal in the repository folder:
   ```bash
   cd "C:\Users\drekt\Documents\Claude et Dylan\Revue médicales décembre 2025"
   ```

2. Check the status of your changes:
   ```bash
   git status
   ```

3. Add the modified file:
   ```bash
   git add index.html
   ```

4. Commit the changes with a descriptive message:
   ```bash
   git commit -m "Update: Add mobile compatibility with hamburger menu"
   ```

5. Push to GitHub:
   ```bash
   git push origin main
   ```

## Method 2: GitHub Web Interface

1. Go to your repository on GitHub.com
2. Navigate to the `index.html` file
3. Click the **pencil icon** (Edit this file)
4. **Delete all content** in the editor
5. Open your local `index.html` file
6. **Copy everything** (Ctrl+A, Ctrl+C)
7. **Paste** into the GitHub editor (Ctrl+V)
8. Scroll to bottom and click **"Commit changes"**
9. Add commit message: "Update: Add mobile compatibility"
10. Click **"Commit changes"** again

## Method 3: Upload via GitHub Web

1. Go to your repository on GitHub.com
2. Click **"Add file"** > **"Upload files"**
3. Drag and drop your new `index.html` file
4. Check **"Replace existing file"** if prompted
5. Add commit message: "Update: Add mobile compatibility"
6. Click **"Commit changes"**

## Verify the Changes

After updating:
1. Wait 1-2 minutes for GitHub Pages to rebuild
2. Visit your site: `https://USERNAME.github.io/REPO-NAME/`
3. Test on mobile to see the hamburger menu
4. Hard refresh: **Ctrl+Shift+R** (or **Cmd+Shift+R** on Mac)

## Quick Commands Summary

```bash
cd "C:\Users\drekt\Documents\Claude et Dylan\Revue médicales décembre 2025"
git add .
git commit -m "Update: Add mobile compatibility with hamburger menu and responsive design"
git push origin main
```
