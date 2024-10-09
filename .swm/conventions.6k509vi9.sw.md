---
title: Conventions
---
# Commit convention

We will follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) rules for commits and PRs:

`<type>(<optional scope>): <commit message>`

`<more specifications if needed>`

| Type                                           | Message   |
| ---------------------------------------------- | --------- |
| A new addition / change                        | *feat*    |
| Fix of a bug / issue                           | *fix*     |
| Revert a commit                                | *revert*  |
| PR draft / not yet approved                    | *draft*   |
| Indicate a breaking change                     | *<type>!* |
| Documentation                                  | *docs*    |
| Redundant tasks (github workflows, tests, ...) | *chore*   |
| Coding style fixes                             | *style*   |

&nbsp;

# How to do a PR

Create the PR **from github** interface. Add the commit with the convention and the people that need to check it. Wait until every (possible) issue with the PR is fixed and merge in the branch wanted.

> Always make a PR when merging into `main`, and get approval of at least one other person

All the information should be in the PR, and the ticket that is linked to the branch should be automatically linked. If someone need more information, add it to the linear ticket.

&nbsp;

# Branches names

### The name of a branch *for a new feature* should be from the linear ticket:

Click on an issue:

<p align="center"><img src="/.swm/images/image-2024-9-9-10-56-5-205.png"></p>

There should be a sidebar on the right, with a `property` line:

<p align="center"><img src="/.swm/images/image-2024-9-9-10-57-11-885.png"></p>

If you click on the top-right icon, you will copy the `branch name`, and you can then create a branch (on this issue:`feature/ca-14-docker-for-dev-local-fastapi`) ![](/.swm/images/image-2024-9-9-10-58-14-602.png)

### For a test branch:

Choose any name that has `test` in it, and a link with the feature to implement. Delete the branch after use

## How to create a branch ?

```bash
git pull
git checkout -b <branch name>
git push -u origin <branch name>
```

You should have the new branch on GitHub

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBTGVuaWEtZG9jcyUzQSUzQUNlbGx1bGFyLUF1dG9tYXRvbg==" repo-name="Lenia-docs"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
