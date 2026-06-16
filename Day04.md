# Git Day 4

## What is a Merge Conflict?

A merge conflict occurs when Git cannot automatically combine changes from different branches.

## Why Do Conflicts Happen?

- Same file edited
- Same lines modified
- Git cannot decide which version to keep

## Conflict Markers

<<<<<<< HEAD
Current branch
=======
Incoming branch
>>>>>>> branch-name

## Commands Learned

git merge
git merge --abort
git log --graph --oneline --all

## Resolution Steps

1. Open conflicted file
2. Remove conflict markers
3. Keep desired content
4. Save file
5. git add
6. git commit

## Key Takeaway

Merge conflicts are normal and can be resolved manually.
