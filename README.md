# Git Reference Sheet – Dat Le (Dawn)
> Quick summary of essential Git commands, workflows, and references.

## 1. Common Commands
| Command | Description |
|----------|-------------|
| `git init` | Create a new repository |
| `git clone <url>` | Copy a remote repo to local machine |
| `git status` | Show changes and tracking state |
| `git add <file>` / `git add .` | Stage changes |
| `git commit -m "message"` | Save staged files |
| `git push origin main` | Upload to remote (GitHub) |
| `git pull origin main` | Fetch and merge updates |
| `git branch <name>` | Create a new branch |
| `git checkout <name>` | Switch branches |
| `git merge <branch>` | Merge into current branch |
| `git log --oneline` | View short commit history |

---

## 2. References

- **Git Cheat Sheet – Education (GitHub Education):** [Download PDF](https://education.github.com/git-cheat-sheet-education.pdf)
- **Git Documentation:** [https://git-scm.com/docs](https://git-scm.com/docs)
- **Markdown-It Documentation:** [https://markdown-it.github.io/](https://markdown-it.github.io/)
- **GitHub Docs – Common Commands:** [https://docs.github.com/en/get-started/using-git/about-git](https://docs.github.com/en/get-started/using-git/about-git)


## 3. Example Tasks

```bash
# Create and push a new project
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/DatLe-2109/git-demo.git
git push -u origin main
# Update project
git pull
git add .
git commit -m "Update files"
git push
# Work on feature branch
git checkout -b feature/ui
# edit...
git add .
git commit -m "Add new UI"
git checkout main
git merge feature/ui
git push



