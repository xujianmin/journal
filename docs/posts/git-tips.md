---
layout: page
title: Git Tips and Tricks
nav_order: 3
---

# Git Tips and Tricks

Useful Git commands and patterns.

## Useful Commands

```bash
# View recent commits
git log --oneline -10

# Undo last commit
git reset --soft HEAD~1

# Stash changes
git stash
git stash pop
```

## Branching Strategy

1. Create a new branch for each feature
2. Merge back to main when ready
3. Delete old branches

## Common Issues

- **Merge conflicts**: Always communicate with your team
- **Lost commits**: Use `git reflog` to recover