# Git Assignment 1

This repository contains the solutions for Assignment 1, focusing on setting up a local Git repository, creating commits, branching, merging, and pushing to a remote repository.

## Assignment Details

### Set up a Local Git Repository

1. Create a new directory on your local machine.
2. Initialize a new Git repository in the directory using the command: `git init`.

### Create Commits

1. Create a new text file named "file1.txt" within the repository directory.
2. Add some content to "file1.txt".
3. Add the file to the staging area using the command: `git add file1.txt`.
4. Commit the changes with a descriptive message using the command: `git commit -m "Add file1.txt"`.

### Create and Switch Branches

1. Create a new branch named "feature" using the command: `git branch feature`.
2. Switch to the "feature" branch using the command: `git checkout feature`.
3. Make changes to "file1.txt" by adding additional content.
4. Commit the changes on the "feature" branch.

### Merge Branches

1. Switch back to the master branch using the command: `git checkout master`.
2. Merge the changes from the "feature" branch into the master branch using the command: `git merge feature`.
3. Resolve any conflicts that may arise during the merge process.

### Push to a Remote Repository

1. Create a remote repository on a hosting platform (e.g., GitHub, GitLab).
2. Add the remote repository URL as a remote named "origin" using the command: `git remote add origin <remote-url>`.
3. Push the local repository to the remote repository using the command: `git push -u origin master`.

## Assignment 2

To complete Assignment 2, follow the steps below:

### Collaborate with Others

1. Share your local repository with a partner or colleague.
2. Have them clone the repository to their local machine.
3. Have them create a new branch, make changes, and commit them.
4. Fetch and merge their changes into your local repository.
5. Resolve any conflicts that may arise during the merge process.
6. Push the local repository to the remote repository using the command: `git push -u origin master`.

## Instructions

1. Clone this repository to your local machine.
2. Complete the assignments as described above.
3. If working with a partner for Assignment 2, ensure effective communication for collaboration.
4. Ensure to follow best practices in commit messages, branch naming, and resolving conflicts.

Feel free to reach out for any clarifications or assistance!
