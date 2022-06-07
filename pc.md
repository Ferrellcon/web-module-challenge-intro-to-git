## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is an open source version control system that is responsible for everything Github-related that happens locally on your computer
2. What is the difference between Git and GitHub?
Git is a version control system that lets you manage and keep track of your source code history while Github is a cloud-based hosting service that lets you manage Git repositories
3. Why do we create a branch?
We create a branch to make a copy of the Git project that we can change as we like and combine it with the original project.
4. What is the purpose of a Pull Request?
Pull requests tells others about changes you've pushed into a branch in a repository on Github. These changes can be reviewed, commented on, and have commits added by contributors, The pull request can be merged if you are happy with the changes.
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
Git switch will undo any changes I make and return to the previous branch. git switch -c <new-branch-name> keeps the changes and continues on a new branch
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Git fetch downloads all history from the remote tracking branches. Git merge combines remote tracking branches into current local branch. Git pull will update your current local working branch with all new commits from the corresponding remote branch on Github.
7. What is a merge conflict?
Merge Conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.
8. How do you resolve a merge conflict?
If you and another person edited the same line in different branches of the same Git repository, open Git Bash, cd to the local Git repository that has the merge conflict, git status to get a list of files affected by the merge conflict, open a text editor and search for the conflict marker <<<<, choose to keep your branch's changes or the other branch's changes or make a new change that combines both changes from the branches, delete conflict markers <<<<, ====, >>>> and make changes you want in the final merge, git add . to add your changes, and commit your changes with a comment using git commit -m

If someone has deleted a file in one branch and another person tries to edit the same file, open Git Bash, cd into the local Git repository that has the merge conflict, git status to get a list of the files affected by the merge conflict, open a text editor and navigate to the file that has merge conflicts, choose if you want to keep the removed file, use git add to add the removed file back to your repository or use git rm to remove the file from your repository, and commit your changes with a comment using git commit -m

