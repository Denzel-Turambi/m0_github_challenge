# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

To establish a connection between a local repository and a remote repository on GitHub, on must follow these steps

1. Create a directory in Terminal and add files to that directory
2. Initialize a Git repository in the selected directory using 'git init'
3. Add your file by using 'git add <filename>'
4. commit your work using 'git commit -m "Message here"
5. Create a GitHub repository with the same name as your directory
6. Run 'git remote add origin <SSH>'
7. Run 'git branch -M main' *if you have not already configured Git to name the default branch 'main'*
8. Run 'git push -u origin main' to send the current version of the porject to the remote repository, and to ste the 'main' branch as the deafualt branch to send work to.
9. Refresh GitHub browser tab, and if done correctly, you should see the new repository!