Git Branching, Merging & History Manipulation – Assignment
This project demonstrates essential Git operations involving branching, merging, conflict resolution, and rewriting commit history using amend and rebase.

Topics Covered
Branching & Merging
Create and switch to new branches (git branch, git checkout)
Make changes in different branches
Merge changes back to the main branch
Handle merge conflicts and resolve them manually
View Git history with git log, git diff, and git show

Conflict Resolution
Simulate conflicts by editing the same file in multiple branches
View conflicted versions using git show :1:, :2:, :3:
Resolve and commit the fixed version

Amending Commits
Fix typos and update previous commits using git commit --amend

Rewriting Commit History
Reorder commits using interactive rebase (git rebase -i HEAD~2)

Undo unwanted commits with git reset --hard using reflog
\\
Key Commands Used
bash
Copy
Edit
git branch
git checkout
git add .
git commit -m "message"
git merge
git diff
git log
git rebase -i HEAD~2
git reset --hard HEAD@{n}
git reflog

Author
Harshul Nihalani
GitHub: @arcgate-harshul
