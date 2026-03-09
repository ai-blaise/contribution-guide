# contribution-guide
This repo will contain rules, guidelines, and helper functions for how we manage projects in this org.

---

## Contents

- [`CONTRIBUTING.md`](CONTRIBUTING.md) — Bash and Fish helper functions for issues, milestones, and pull requests

---

## Setup

Copy the functions for your shell from [`CONTRIBUTING.md`](CONTRIBUTING.md) into your config file:

```bash
# Bash
~/.bashrc or ~/.bash_profile

# Fish
~/.config/fish/config.fish
```

Once added, open a new terminal and verify everything is working:

```bash
gh auth status
list_issues
```

---

## Available Functions

| Function | Description |
|---|---|
| `create_issue <project> <org> <title> <body>` | Create an issue and add it to the board |
| `assign_milestone <issue> <milestone>` | Assign an issue to a milestone |
| `close_issue <issue>` | Close an issue |
| `list_issues` | List all open issues |
| `create_milestone <org> <repo> <title> <date>` | Create a milestone |
| `list_milestones <org> <repo>` | List all milestones |
| `milestone_issues <milestone>` | List issues under a milestone |
| `create_pr <title> <issue> <reviewer>` | Open a PR that closes an issue |
| `check_pr <pr>` | Check CI status on a PR |
| `approve_pr <pr>` | Approve a PR |
| `request_changes <pr> <comment>` | Request changes on a PR |
| `merge_pr <pr>` | Merge a PR |
| `list_prs` | List all open PRs |
