# CONTRIBUTING
These are our guidelines for contributing to our repositories. It's very important that you follow these guidelines, it ensures that your pull-request is accepted, and it helps us maintain a quality codebase for each project.

### Our Code Of Conduct
For the safey of our team members and project contributors our code of conduct (see: https://github.com/dibblit/CONTRIBUTING/blob/master/CODE_OF_CONDUCT.md) must be followed at all times. People who violate our code of conduct may be warned and risk further action such as losing your team member status and/or being blocked from contributing to the project as decided by organization management.

### How to contribute a change to a project's codebase
When working on a change to code in one of our repositories you will need to do the following:
1. Fork the repository into your account 
2. Make the change to your fork
3. Make a pull-request for the changes to be merged into the our repository. 

Please keep the following in mind when changing our codebase and making a pull request:

* Always make your edits to a branch (Use `git checkout -b patch-n` with n being a number you haven't used before - it's recommended to start at one and increment up) and never commit directly to master. This is VERY IMPORTANT because in the rare case that your PR is rejected your copy of the master branch will be forever uneven with our master branch (the only way to fix it is to delete your fork and re-fork). Since you are working on a branch be sure to run `git checkout master` before switching to another new branch.

* Only create one commit per pull request - if you've already made multiple commits you'll need to 'squash' them into a single commit. (See: https://github.com/ginatrapani/todo.txt-android/wiki/Squash-All-Commits-Related-to-a-Single-Issue-into-a-Single-Commit for information on doing that.)

* To avoid having to constantly delete your fork and refork to have the latest changes please add the main repository as an upstream (`git remote add upstream https://github.com/dibblit/repoNameHere.git`) and rebase your copy of master (`git checkout master`, `git pull --rebase upstream master`) before making a new branch

* If you are a maintainer for a specific project and have write access to the repository - please do not commit directly to the repository (this includes 'tiny' changes) - pull requests allow time for code review and input from other members of the project who have feedback - just like other members you will need to create a fork and perform a pull request keeping the above guidelines in mind.

### Other resourcs
You might find the following resources useful if this is your first time contributing to a project using GitHub:
* https://guides.github.com/
* https://www.udacity.com/course/how-to-use-git-and-github--ud775
