## 1. Introduction to Git

    ## 1.1 First navigate to your project directory with the "cd <directory>" command or open a cmd instance in the project folder.
    ## 1.2 Use the command "git init". The command initializes a new Git repository in your current directory.
    ## 1.3 Add this file (README.MD) to the staging area using the command "git add README.MD".
    ## 1.4 Use the command "git commit -m "comment"" to commit changes. Replace "comment".
    ## 1.5 Check status of your repository with "git status". README.MD should be listed as modified or new file.
    ## 1.6 Run "git add -A" to stage all changes in the repository. Alternatively run "git status" again to see the changes, if the README.MD is untouched you should see the output: 
    On branch master
    Changes to be committed:
    (use "git restore --staged <file>..." to unstage)
            modified:   README.MD