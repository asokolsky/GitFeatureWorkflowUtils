# GitFeatureWorkflowUtils
Schell scripts supporting "Feature Branch Workflow"

## Manual Installation
Copy the cripts into your 
~/bin
chmod a+x

Enjoy!

## Usage
Assume that you are to develop a Jira issue JRA-888

### Start
git-st JRA-888

This will 
 - update local master and 
 - create/switch to branch JRA-888

### Develop & Commit
git status
git add file1
git-com

The latter will commit the changes to the current branch with a message=branch
