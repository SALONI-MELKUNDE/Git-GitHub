# Remote 🌟 ------------------------------->>>>> Local

# Git Commands Explained:

*1. git config --global user.name '.......'*

Purpose: Sets the global username for Git.
Use Case: Configure your identity for commits. Replace ....... with your desired name.
Example: git config --global user.name 'John Doe'

*2. git config --global user.email '.......'*

Purpose: Sets the global email for Git.
Use Case: Connect your email to your commits. Replace ....... with your email address.
Example: git config --global user.email 'johndoe@example.com'

*3. git config --list*
Purpose: Lists all global Git configurations.
Use Case: Verify your username and email settings.

*4. Create a new repository on GitHub*
Purpose: Set up a remote repository on GitHub.
Use Case: Go to GitHub, create a new repository (e.g., "my-project"), and copy the repository link (HTTPS or SSH).

*5. git clone <link>*

Purpose: Downloads a remote repository to your local system.
Use Case: Replace <link> with the URL of the GitHub repository you created.
Example: git clone https://github.com/username/my-project.git
Outcome: This will create a local copy of the repository on your system.

*6. Now you can see all files in your system*

Purpose: Confirm that the repository files have been downloaded locally.
Use Case: Use ls or navigate to the project directory to check the files.

*7. Make changes to the files (e.g., in VS Code)*

Purpose: Modify files locally as needed.
Use Case: Open the project in a code editor like VS Code to edit or add content.

*8. git add .*

Purpose: Stages all changes made in the repository.
Use Case: Use this after editing files to prepare them for committing.
Example: git add . stages all files in the current directory.

*9. git commit -m '.....'*

Purpose: Records the staged changes with a message.
Use Case: Replace ..... with a meaningful commit message describing the changes.
Example: git commit -m 'Updated README file'

*10. git push original main*
Purpose: Pushes your committed changes from the local system to the remote repository.
Use Case: Upload your updated files to GitHub.
Example: git push original main

*11. git status*

Purpose: Displays the status of your repository.
Use Case: Use this to check if there are any uncommitted changes or staged files.

Happy Learning! 💻 🚀
