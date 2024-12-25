# Git Workflow for Syncing Local and Remote Repositories

When you try to push local changes to a GitHub repository, but the push is rejected because the remote repository has changes that you don't have locally, you need to **pull** those changes first. Here's how to handle this process:

## Steps to Integrate Remote Changes and Push Local Changes

### 1. **Pull the Latest Changes from the Remote Repository**
To ensure your local repository is up-to-date with the remote repository, run the following command in your local project directory:

```bash
git pull origin main --rebase
```
### 2. Resolve Merge Conflicts (If Any)
###
```bash
git add <filename>
git rebase --continue

```
### 3. Push Your Local Changes to GitHub
```bash
git push origin main
```

