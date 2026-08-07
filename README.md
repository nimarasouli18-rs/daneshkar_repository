# Homework Git - Week 10

This repository contains the completed Git homework exercises for Week 10.

## Project Structure

The project is divided into eight main sections:

* `01_basics` — Git installation, configuration, repository creation, and atomic commits.
* `02_commits` — Working with `git add`, `git commit`, `git diff`, and `git commit --amend`.
* `03_branching` — Creating, switching, renaming, and deleting branches.
* `04_merging` — Fast-forward merge, merge commits, and conflict resolution.
* `05_stash` — Temporarily storing and restoring uncommitted changes using Git Stash.
* `06_diff_history` — Inspecting changes, comparing commits and branches, and working with detached HEAD.
* `07_reset_revert` — Restoring files and understanding `git reset` and `git revert`.
* `08_github` — Connecting a local repository to GitHub, pushing, pulling, and collaboration.

## Key Concepts

### Atomic Commits

An atomic commit represents one logical and complete change. This makes the project history easier to understand and maintain.

### Branching Strategy

Branches allow developers to work on different features or changes independently without affecting the main branch.

### Merge vs Rebase

Merge combines the histories of branches, while rebase moves commits onto a new base to create a more linear history.

### Conflict Resolution

A merge conflict occurs when Git cannot automatically combine changes. Conflicts must be reviewed and resolved manually before completing the merge.

### GitHub Workflow

A common GitHub workflow includes creating a local repository, committing changes, connecting it to a remote repository, pushing changes, and pulling remote updates.

## Common Git Commands

```bash
git init
git status
git add .
git commit -m "commit message"

git branch
git switch main
git switch -c feature

git merge branch-name
git stash
git stash list
git stash apply

git diff
git diff --staged
git log --oneline
git log --oneline --graph --all

git reset
git revert

git remote -v
git push
git pull
git fetch
```

## Submission Contents

This repository includes:

* Git repositories for all exercises
* Markdown files containing conceptual explanations
* TXT files containing important command outputs
* `log_commands_git.txt` containing the Git commands used during the exercises
* This `README.md` file

## Author

Nima Rasouli
