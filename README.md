To push this code to Git, follow these steps:

1. **Navigate to Your Project Directory**: Open Git Bash or your terminal in the root folder of your Android Studio project.

2. **Initialize Git (if necessary)**: If you haven’t already initialized Git in this directory, run:
   ```bash
   git init
   ```

3. **Add All Files**: Add all files to the Git staging area:
   ```bash
   git add .
   ```

4. **Commit the Changes**: Commit your changes with a descriptive message:
   ```bash
   git commit -m "Add USN validation and navigation logic in ScreenA"
   ```

5. **Link Your GitHub Repository (if not already linked)**:
   - Create a repository on GitHub if you haven't yet. Do not add a README if your local project already has one.
   - Copy the repository URL from GitHub.
   - Link the local repository to the GitHub remote repository:
     ```bash
     git remote add origin <your-repo-URL>
     ```

6. **Push to GitHub**: Push your changes to the GitHub repository on the `main` or `master` branch:
   ```bash
   git push -u origin main
   ```
   If your branch is named `master`, replace `main` with `master`.

7. **Verify on GitHub**: Go to your GitHub repository page and refresh. Your code should now be uploaded!

Let me know if you run into any issues with these steps.
