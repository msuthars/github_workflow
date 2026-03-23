# Description

This is repository is about to test the github workflows.
 
## Claude QA

The claude-qa workflow is triggered only when a comment containing @claude is added to the merge request.
This initiates automated testing and code review for the MR.
The workflow runs only against the default branch.

To enable this workflow, the `CLAUDE_CODE_OAUTH_TOKEN` secret must be configured at the repository level.

### Claud QA test result

After adding @claude to the merge request, Claude will start testing the site based on the given instructions or test steps.

Test Steps: https://github.com/msuthars/github_workflow/pull/2#issue-3869447361

Result: https://github.com/msuthars/github_workflow/pull/2#issuecomment-3822478575
