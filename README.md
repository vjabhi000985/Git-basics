# Git and GitHub Tutorial

This simple tutorial will walk you through the process of initializing a Git repository, adding text files, and pushing your changes to a GitHub repository.

## Steps

1. **Navigate to your Desired Directory:**
   - Open your terminal and navigate to the directory where you want to create your Git repository.

2. **Add Text Files:**
   - Create and add the necessary text files to your chosen directory.

3. **Initialize a Git Repository:**
   - Run the following command to initialize a new Git repository in your current directory:
     ```shell
     git init
     ```

4. **Add Changes:**
   - Add your files to the staging area using either:
     - To add all files:
       ```shell
       git add .
       ```
     - To add specific files:
       ```shell
       git add filename
       ```

5. **Commit Changes:**
   - Commit your staged changes with a meaningful message using:
     ```shell
     git commit -m "First Commit"
     ```

6. **Set Remote Origin:**
   - Link your local repository to a GitHub repository by running:
     ```shell
     git remote add origin https://github.com/ihechikara/git-and-github-tutorial.git
     ```

7. **Rename the Default Branch:**
   - Change the default branch name from "master" to "main" with:
     ```shell
     git branch -M main
     ```

8. **Push to GitHub:**
   - Finally, push your local repository to GitHub with:
     ```shell
     git push -u origin main
     ```

Follow these steps to get started with Git and GitHub. This tutorial will help you with the basics of version control. Enjoy your coding journey!
