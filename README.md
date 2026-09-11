# Delivery Practices with Emerging AI — Lab Guide

A step-by-step guide to working with GitHub: creating a repository, adding files, working with branches, and merging pull requests.

## Prerequisites

- A GitHub account (create one at [github.com](https://github.com) if you don't have one)

## 1. Create a GitHub Repository

1. Sign in to your GitHub account.
2. Click **New repository**.
3. Name the repository (e.g., `demoproject`).
4. Set the visibility to **Public**.
5. Check the option to initialize the repository with a **README** file.
6. Click **Create repository**.

## 2. Add a New File

1. In your repository, click **Add file** → **Create new file**.
2. Name the file `samplecode.sh`.
3. Add the following sample code:

   ```bash
   echo "Welcome to the demo project"
   ```

4. Scroll down to **Commit changes**.
5. Select **Create a new branch for this commit and start a pull request**.
6. Name the new branch `develop`.
7. Click **Propose changes**.
8. Add a meaningful comment describing the change.
9. Click **Create pull request**.
10. Review the pull request, then click **Merge pull request** and **Confirm merge**.
11. The pull request is now merged and closed.
12. Navigate to the **main** branch to verify that `samplecode.sh` was added successfully.

## 3. Edit an Existing File

1. Go to the **develop** branch using the branch dropdown.
2. Open `samplecode.sh`.
3. Click the **Edit file** (pencil) icon.
4. Modify the file content — for example, add a new line of code.
5. Click **Preview changes** to review the edits. Added lines will be highlighted in green.
6. Scroll down and add a meaningful commit comment.
7. Click **Commit changes**.

## 4. Merge Changes from `develop` into `main`

1. Navigate to the **main** branch.
2. GitHub will prompt you to create a pull request for the recent changes on `develop` — click **Compare & pull request**.
3. Review the changes, then click **Merge pull request** and **Confirm merge**.
4. The pull request is now merged and closed.
5. Navigate to the **main** branch and open `samplecode.sh` to verify the updated content.

## Summary

This lab covers the core GitHub delivery workflow:
- Creating a public repository
- Adding a new file via a feature branch (`develop`) and pull request
- Editing an existing file on a branch
- Merging changes back into `main` via a pull request

This branch → pull request → merge cycle reflects a standard collaborative development workflow used in real-world software delivery.
