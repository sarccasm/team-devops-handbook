# Git Branching Conventions

## Branch naming

Branches should follow this format:

- feature/<name>-<task>
- bugfix/<name>-<task>
- hotfix/<task>

Examples:

feature/add-readme
bugfix/fix-parser


## Commit messages

Use clear commit prefixes:

feat: add new feature

fix: fix a bug

docs: update documentation


## Before merging

Before creating a pull request:

1. Check git status
2. Pull latest changes from main
3. Resolve conflicts if needed
4. Run tests