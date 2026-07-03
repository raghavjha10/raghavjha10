# Raghav Jha's GitHub Profile Setup Guide

This guide will walk you through the process of setting up your premium GitHub profile README.

## Prerequisites

1. A GitHub account with the username **raghavjha10**.
2. Git installed on your computer.

---

## Step 1: Create the Special Repository

1. Go to [GitHub - New Repository](https://github.com/new).
2. Set the **Repository name** to exactly: `raghavjha10`
   > [!IMPORTANT]
   > It must match your GitHub username exactly. GitHub will show a special box saying: *"You found a secret! raghavjha10/raghavjha10 is a special repository..."*
3. Make sure the repository is set to **Public** (Private repositories will not display the README on your profile).
4. **Do NOT** initialize it with a README, `.gitignore`, or license since we already have the files prepared here.
5. Click **Create repository**.

---

## Step 2: Push the Files to GitHub

We will push the files in this directory to your new repository.

Open your command prompt or terminal in the `raghavjha10` project directory and run the following commands:

```bash
# Initialize a new Git repository
git init

# Add all files to the staging area
git add .

# Create the initial commit
git commit -m "feat: initial commit of premium profile readme"

# Rename branch to main
git branch -M main

# Add the remote repository (Replace with your actual repo link if different)
git remote add origin https://github.com/raghavjha10/raghavjha10.git

# Force-push the main branch (Warning: This will overwrite any existing content in that repository)
git push -u origin main -f
```

---

## Step 3: Configure GitHub Actions Permissions

For the contribution snake to generate twice a day and update your README, the GitHub Actions runner needs write permissions to push to your repository.

1. Go to your repository settings on GitHub: `https://github.com/raghavjha10/raghavjha10/settings`.
2. On the left sidebar, click on **Actions** -> **General**.
3. Scroll down to **Workflow permissions**.
4. Change the setting to **Read and write permissions**.
5. Click **Save**.

---

## Step 4: Run the Snake Action for the First Time

To verify that the snake contribution animation is working and to generate it immediately:

1. Click on the **Actions** tab of your repository: `https://github.com/raghavjha10/raghavjha10/actions`.
2. Under the Actions list on the left, click on **Generate Snake**.
3. On the right, click the **Run workflow** dropdown and then click the green **Run workflow** button.
4. Wait about 30 seconds for the action to complete successfully. It will create a new branch named `output` containing the animated SVG files.
5. Visit your main GitHub profile page (`https://github.com/raghavjha10`) to see your stunning, new, animated profile!

---

## Customize Links in your README.md

Open [README.md](file:///C:/Users/LENOVO/.gemini/antigravity/scratch/raghavjha10/README.md) and replace the following placeholders with your actual links:
- `YOUR_LINKEDIN_USERNAME` with your LinkedIn handle (e.g. `raghav-jha-123456`)
- `YOUR_LEETCODE_USERNAME` with your Leetcode handle (e.g. `raghavjha10`)
- `YOUR_EMAIL@gmail.com` with your active email address.
