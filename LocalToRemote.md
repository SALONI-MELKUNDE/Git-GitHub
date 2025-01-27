# Local ------------------------------->>>>> Remote🌟

# Git Commands Explained:

*1. mkdir [dir]*

Purpose: Creates a new directory (folder).
Use Case: This is where your project files will reside. Replace <dir> with the desired directory name.
Example: mkdir my-project will create a folder named "my-project."

*2. cd [dir]*

Purpose: Navigates into the newly created directory.
Use Case: Switch to the project directory to start working within it.
Example: cd my-project will move into the "my-project" folder.

*3. ls*

Purpose: Lists the contents of the current directory.
Use Case: Use this to confirm the contents of the directory or check what files are present.

*4. ls -a*

Purpose: Lists all files and directories, including hidden files (those starting with a dot .).
Use Case: Hidden files like .git will be visible when using this command, which is useful after initializing a Git repository.

*5. git init*
   
Purpose: Initializes a new Git repository in the current directory.
Use Case: Prepares the directory for version control. It creates a hidden .git folder where Git stores all version history and configurations.

*6. ls -a*
   
Purpose: Lists all files and directories, including hidden ones, to confirm the creation of the .git folder.
Use Case: After running git init, use this to verify that the .git folder has been created, indicating that the directory is now a Git repository.

*7. Create a repository on GitHub and copy its link*
    
Purpose: Set up a remote repository on GitHub to store your project online.
Use Case: Navigate to GitHub, create a new repository (e.g., "my-project"), and copy the repository link (HTTPS or SSH). This will be used to link the local repository to the remote one.

*8. git remote add original [link]*

Purpose: Links your local Git repository to the remote repository.
Use Case: Replace <link> with the copied repository URL (e.g., https://github.com/username/my-project.git). The alias original is used to refer to the remote repository.

*9. git remote -v*
    
Purpose: Displays the remote repositories linked to your local repository.
Use Case: Use this to verify that the remote repository has been added correctly and to check its details (fetch and push URLs).

*10. git branch*

Purpose: Displays the current branch of your repository.
Use Case: Ensure that you are on the correct branch (usually main by default) before pushing your changes.

*11. git push original main*

Purpose: Pushes your changes from the local main branch to the remote repository.
Use Case: Uploads your project files and version history to GitHub, making them available online.



Happy Learning! 💻 🚀
