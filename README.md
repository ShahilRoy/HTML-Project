# How to Upload This Folder to GitHub

Follow these steps to upload this project to GitHub:

## Step 1: Create a GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in to your account.
2. Click the "+" icon in the top right corner and select "New repository".
3. Give your repository a name (e.g., "html-project").
4. Add a description if you want.
5. Choose whether to make it public or private.
6. Do NOT initialize with a README, .gitignore, or license (since we already have files).
7. Click "Create repository".

## Step 2: Initialize Git in Your Local Folder
1. Open a terminal/command prompt in this folder (c:/Users/Shahil/Desktop/HTML).
2. Run the following commands:

```bash
git init
git add .
git commit -m "Initial commit"
```

## Step 3: Connect to GitHub Repository
1. Copy the repository URL from GitHub (it should look like https://github.com/yourusername/yourrepo.git).
2. In your terminal, run:

```bash
git remote add origin https://github.com/yourusername/yourrepo.git
git push -u origin master
```

## Step 4: Verify Upload
1. Go back to your GitHub repository page.
2. You should see your files (index.html, first.js, README.md) uploaded.

## Notes
- Replace "yourusername" and "yourrepo" with your actual GitHub username and repository name.
- If you encounter any issues, make sure Git is installed on your system.
- For more detailed instructions, check GitHub's official documentation.
