# Git Commands: Advanced Usage

*1. git branch*

Purpose: Lists all branches in your repository.
Use Case: Use this command to view all branches and check which branch you are currently on. The active branch will have an asterisk * next to it.

*2. git branch -M main*

Purpose: Renames the current branch to main.
Use Case: If your default branch is named master or something else, use this to rename it to main, the modern default naming convention.

*3. git checkout <branch-name>*

Purpose: Switches to the specified branch.
Use Case: Use this command to move between branches in your project. Replace <branch-name> with the branch you want to switch to.

*4. git branch -d <branch-name>*
    
Purpose: Deletes a branch locally.
Use Case: Use this to clean up branches you no longer need. Replace <branch-name> with the name of the branch you want to delete.

*5. git checkout -b feature1*
Purpose: Creates and switches to a new branch called feature1.
Use Case: Use this command to create a new branch for working on a specific feature or bug fix.

*6. Pull Request Definition*
A Pull Request (PR) is a method of proposing changes to a repository. It allows developers to collaborate by reviewing code before merging it into the main branch.

Steps to Create a Pull Request:

a. Create a new branch and push changes to it.
b. Go to the repository on GitHub.
c. Click on "Pull Requests", then "New Pull Request".
d. Select the branch to compare and propose the changes.
e. Submit the pull request for review.

*7. Undoing Stages and Changes*

*a) Undo Staged Changes*

Command:

```bash
git restore --staged <file>
```

Purpose: Unstages a file but keeps the changes in the working directory.

Example:

```bash
git restore --staged README.md
```

*b) Discard Changes in a File*

Command:

```bash
git restore <file>
```

Purpose: Discards changes in the working directory and restores the file to its last committed state.

Example:

```bash
git restore README.md
```

*c) Undo the Last Commit (Keep Changes in Staging)*

Command:

```bash
git reset --soft HEAD~1
```

Purpose: Moves the last commit back to the staging area, allowing you to re-commit with changes if needed.

Example:

```bash
git reset --soft HEAD~1
```

*d) Undo the Last Commit (Discard Changes Permanently)*

Command:

```bash
git reset --hard HEAD~1
```

Purpose: Completely removes the last commit and all associated changes.

Example:

```bash
git reset --hard HEAD~1
```

*e) Check Status Before Undoing Changes*

Command:

```bash
git status
```

Purpose: Always check the repository status before undoing actions to avoid unintentional data loss.

Example:

```bash
git status
```

Happy Coding and Collaboration! 💻🚀







