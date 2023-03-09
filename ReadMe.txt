1. how to create a new github repository?

Creating a new GitHub repository is a simple process that can be done through the GitHub website. Here are the steps:

    First, log in to your GitHub account.
    Click on the "+" icon on the top right corner of the page and select "New repository".
    Give your repository a name and a short description (optional).
    Choose whether you want your repository to be public or private.
    Choose whether to initialize the repository with a README file.
    Choose a license for your repository, if you wish to do so.
    Click on the "Create repository" button.

Your new repository is now created and you can start adding files, creating branches, and making commits to your repository.

2. How to add a project from vs code?

To add a project from VS Code to GitHub, you will need to follow these steps:

    Create a new repository on GitHub. You can follow the steps I mentioned earlier to create a new repository on GitHub.

    Open the terminal in VS Code by pressing `Ctrl + Shift + ``. This will open the integrated terminal in VS Code.

    Navigate to the folder where your project is located using the cd command. For example, if your project is located in the Documents folder, you can type cd Documents in the terminal.

    Initialize a new Git repository by typing git init in the terminal. This will create a new Git repository in the current folder.

    Add all the files in your project to the Git repository using the git add . command. This will stage all the files in your project for the first commit.

    Commit the changes using the git commit -m "Initial commit" command. This will create the first commit in your Git repository.

    Add the remote repository by typing git remote add origin <repository URL> in the terminal. Replace <repository URL> with the URL of the repository you created in step 1.

    Push the changes to the remote repository using the git push -u origin master command. This will push the changes to the remote repository and set the upstream branch to master.

After completing these steps, your project will be added to the GitHub repository you created in step 1. You can now manage your project using Git and GitHub from within VS Code.
