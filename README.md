# Description

This is repository is about to test the github workflows.
 
## Claude QA

The claude-qa workflow is triggered only when a comment containing @claude is added to the merge request.
This initiates automated testing and code review for the MR.
The workflow runs only against the default branch.

To enable this workflow, the `CLAUDE_CODE_OAUTH_TOKEN` secret must be configured at the repository level.
