## Pushing a Folder to GitHub

1. **Create a Repository on GitHub:**
   - Go to GitHub and log in.
   - Click on the "+" icon in the top-right corner and select "New repository."
   - Give your repository a name, optionally add a description, choose if it's public or private, and then click "Create repository."

2. **Initialize a Local Git Repository:**
   - Open your terminal or command prompt.
   - Navigate to the folder containing the files you want to push to GitHub using the `cd` command.
   - Initialize a Git repository in that folder using the command: 
     ```
     git init
     ```

3. **Add Files to the Staging Area:**
   - Add the files you want to push to the staging area using the command:
     ```
     git add .
     ```
   - The "." adds all files. You can also specify individual files or use wildcards.

4. **Commit the Files:**
   - Commit the files to the local repository with a meaningful message describing the changes, using the command:
     ```
     git commit -m "Your commit message here"
     ```

5. **Link Local Repository to GitHub Repository:**
   - Go back to your GitHub repository page and copy the repository's URL.
   - In your terminal, link your local repository to the GitHub repository using the command:
     ```
     git remote add origin <repository_URL>
     ```

6. **Push Changes to GitHub:**
   - Push the committed changes from your local repository to the GitHub repository using the command:
     ```
     git push -u origin main
     ```
   - If you're using a different branch, replace "main" with the name of your branch.

7. **Verify on GitHub:**
   - Refresh your GitHub repository page, and you should see your files there.

Remember, you may need to authenticate with your GitHub username and password during the `git push` step, especially if it's your first time pushing to this repository from your current machine. If you're using SSH authentication, you won't need to enter your credentials each time.
