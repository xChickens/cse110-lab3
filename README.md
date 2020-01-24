1. What is the difference between Git and GitHub?
Git itself is a version control system, which does not require internet and is contained in its own workspace, having its own local repository.
Github is a remote repository, meaning its connected to the internet and allows for collaboration with others or a team.

2. What is the difference between a commit and a push?
A commit saves all changes on the staging area to a local repository. On the other hand, a push uploads those commits to a remote repository.

3. What is a feature branch?
A feature branch is a branch separate from master, made specifically to allow separation of features, allowing for the ability to push
the single feature to master without any conflicts. It can be used to develop the feature separately as well.

4. What does it mean to protect your master branch, and why would you want to do that?
Protecting the master branch means preventing changes from being pushed without an approving review.
This should be used in order to prevent changes to production code without another pair of eyes looking at it, as a single person makes
mistakes, and we would not want to break all the code on accident.

5. What is the typical workflow of pulling modified files off of github, making changes and pushing the changes back to the github repository?
The typical workflow is to always pull before making any pushes. One may make changes at any time before pushing, but in order to push
code to the github repository, we should resolve conflicts beforehand.
The typically flow would be: git pull, modify, git add, git commit, git push
