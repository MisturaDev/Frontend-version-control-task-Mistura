# Frontend-version-control-task-Mistura
## Purpose of the Repo

This repository demonstrates my understanding of version control workflows, Git commands, branch management, pull requests, merging and reversion practices. 
It simulates a frontend project with a header and footer feature.

---

## Branch Names & Purpose

| Branch Name                                            | Purpose                                               |
| ------------------------------------------------------ | ----------------------------------------------------- |
| `main`                                                 | Base branch where all final code is merged            |
| `feature-header`                                       | Implement and style the header section of the webpage |
| `feature-footer`                                       | Implement and style the footer section of the webpage |


---

## Git Commands Used Most Frequently
```bash
- git branch – check local branches

- git checkout <branch> – switch branches

- git branch -m <old> <new> – rename a branch

- git add <file> – stage changes

- git commit -m "<message>" – commit staged changes

- git push origin <branch> – push commits to remote

- git push origin --delete <branch> – delete remote branch

- git merge <branch> – merge a branch into current branch

- git revert <commit> – undo a commit by creating a new revert commit

- git stash / git stash pop – temporarily save local changes
```

---

## Pull Requests & Merges
- Two feature branches were merged into main via pull requests:
  1. feature-header - main
  2. feature-footer - main

- Review comments were added for the footer PR to simulate a review process.


---

## Reversion & Cleanup
- Demonstrated a revert commit: added a minor comment in index.html and then reverted it.

- Demonstrated a branch rename:
  feature-header - feature-header-renamed

---

## Lessons Learned
- Git allows safe experimentation with features via branches.

- Pull requests enable review and discussion before merging into main.

- Revert commits are useful for undoing mistakes without altering history.

- Branch renaming and remote cleanup help maintain a clear repository structure.

- Frequent commits with descriptive messages make collaboration and tracking easier.


