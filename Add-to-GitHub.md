# Adding to GitHub

1. Create a new repository on GitHub. 
To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.

1. Open Terminal
1. Change the current working directory to your local project.

1. Initialize the local directory as a Git repository.

```
$ git init

```
1. Add the files in your new local repository. This stages them for the first commit.

```
$ git add .

# Adds the files in the local repository and stages them for commit. 
# To unstage a file, use 'git reset HEAD YOUR-FILE'.
```
1. Commit the files that you've staged in your local repository.

```
$ git commit -m "First commit"

# Commits the tracked changes and prepares them to be pushed to a remote repository. 
# To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
```
