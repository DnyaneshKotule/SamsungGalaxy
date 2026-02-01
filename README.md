# SamsungGalaxy
This repository has been created for practicing C language and Java programming.
//🔑 Basic Git Commands
- git init → Initialize a new Git repository
- git clone <repo-url> → Clone an existing repository
- git status → Show the working directory status
- git add <file> → Stage changes for commit
- git commit -m "message" → Commit staged changes
- git log → Show commit history
- git diff → Show changes between commits or working directory

🌐 Remote Repository Commands
- git remote add origin <url> → Add a remote repository
- git remote -v → List remote repositories
- git push origin <branch> → Push commits to remote
- git pull origin <branch> → Fetch and merge changes from remote
- git fetch → Download objects and refs from another repository

🔀 Branching & Merging
- git branch → List branches
- git branch <name> → Create a new branch
- git checkout <branch> → Switch to a branch
- git checkout -b <branch> → Create and switch to a new branch
- git merge <branch> → Merge a branch into the current one
- git rebase <branch> → Reapply commits on top of another base branch

🛠️ Undoing & Fixing
- git reset <file> → Unstage a file
- git reset --hard <commit> → Reset to a specific commit (dangerous!)
- git revert <commit> → Create a new commit that undoes changes
- git stash → Temporarily save changes
- git stash pop → Reapply stashed changes

📦 Advanced / Useful Commands
- git tag <name> → Create a tag
- git show <commit> → Show details of a commit
- git blame <file> → Show who changed each line
- git cherry-pick <commit> → Apply a specific commit from another branch
- git bisect → Find the commit that introduced a bug

👉 GitHub adds extra functionality like pull requests, issues, actions, and project boards, but those are managed through the GitHub web interface or GitHub CLI (gh).

⚡ GitHub CLI (gh) Commands
If you install GitHub’s CLI tool (gh), you can run:
- gh repo clone <repo> → Clone a repo
- gh issue create → Create a new issue
- gh pr create → Create a pull request
- gh pr checkout <id> → Check out a pull request locally
- gh release create <tag> → Create a release
