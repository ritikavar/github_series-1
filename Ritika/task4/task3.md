# what is meant by fork and clone?
 Git Fork means you just create a copy of the main repository of a project source code to your own GitHub profile.
 The "clone" command downloads an existing Git repository to your local computer.
# what are branches in github?
The way git, and GitHub, manage this timeline — especially when more than one person is working in the project and making changes — is by using branches. A branch is essentially is a unique set of code changes with a unique name. Each repository can have one or more branches. ... One word: the master branch is deployable
# what is pull request?
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows.
# can be delete the master branch if not why?
No we cannot delete the master branch beacuse its a default branch.
# how can be delete branch ?
.If we want to delete it Locally . We can delete if only pushed and merged with remote by command: git branch -d localBranchName
use git -D  if we  force branch to be deleted.
And if we want yo  delete branch remotely
use commamd git push <origin> -deletion <remoteBranchName>