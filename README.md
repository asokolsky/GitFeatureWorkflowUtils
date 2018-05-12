# Git Feature Branch Workflow Utils
Schell scripts supporting "Feature Branch Workflow" described here:

https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow

## Manual Installation
Copy the cripts into your 
~/bin
chmod a+x

Enjoy!

## Usage
Assume that you are to develop a Jira issue JRA-888

#### Start
git-st JRA-888

This will 
 - update local master and 
 - create/switch to branch JRA-888

#### Develop & Commit
git status
git add file1
git-com

The latter will commit the changes to the current branch with a message=branch

#### Catch Up with the changes made on trunk
git-cu

This will checkout master, pull from origin.  Then checkout back to the branch and do rebase.
