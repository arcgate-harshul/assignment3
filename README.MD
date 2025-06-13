Git Branching & History – Mini Project
This project demonstrates essential Git operations like branching, merging, conflict resolution, and rewriting history.

Branching & Merging
Create & switch branches:
git branch, git checkout

Commit changes:
git add ., git commit -m "message"

Merge branches:
git merge branch-name

View history:
git log --oneline

⚔️ Merge Conflicts
Check conflict versions:
git show :1:file, :2:, :3:

See conflicts:
git diff

Resolve & commit:
git add file, git commit

✏️ Amend & Rebase
Fix last commit:
git commit --amend

Reorder commits:
git rebase -i HEAD~2

Undo with reflog:
git reflog, git reset --hard HEAD@{n}

Author: Harshul Nihalani
GitHub: @arcgate-harshul
