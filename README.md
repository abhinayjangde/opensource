## opensource contributions


### Important difference
Just writing #6 in a PR description usually creates a reference/link, but it may not close the issue automatically. Use a closing keyword plus the number:

| PR text       | Result after merge to main                  |
| ------------- | ------------------------------------------- |
| Related to #6 | Links/references the issue; may remain open |
| Fixes #6      | Automatically closes issue #6               |
| Closes #6     | Automatically closes issue #6               |
| Resolves #6   | Automatically closes issue #6               |

If it is still open
It is completely fine to close it manually. Add a short final comment such as:

text
Fixed in PR #<pull-request-number>. Closing this issue.
Then click Close issue. This is good repository management because it shows contributors that their work was merged and the task is completed.

For future PRs, ask contributors to add Fixes #issue-number in the PR description. GitHub can auto-close linked issues by default, although repository maintainers can disable that setting under Settings → General → Issues.