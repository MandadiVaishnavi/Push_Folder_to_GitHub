# Push_Folder_to_GitHub
1. **Create a Repository on GitHub**
2. **Initialize a Local Git Repository:**
   ```
    git init
   ```
3. **Add Files to the Staging Area:**
     ```
     git add .
     ```
4. **Commit the Files:**
     ```
     git commit -m "Your commit message here"
     ```
5. **Link Local Repository to GitHub Repository:**
     ```
     git remote add origin <repository_URL>
     ```
6. **Push Changes to GitHub:**
     ```
     git push -u origin main
     ```
7. **Verify on GitHub**


# Troubleshooting
**If you encounter issues while pushing:**

**Unable to push?**
```
git pull origin main
```
This command fetches and merges changes from the remote repository.

**Error: fatal: refusing to merge unrelated histories:**
```
git pull origin main --allow-unrelated-histories
```
Then try pushing your files again using:
```
git push -u origin main
```
