##Git Commands List 📋

Here’s a fully formatted list of Git commands with explanations and emojis for easy reference.

---

## ⚙️ Configuration Commands
- **`git config --global user.name "Your Name"`**  
  🛠️ Sets the name for Git commits globally on your system.  
- **`git config --global user.email "you@example.com"`**  
  🛠️ Sets the email address for Git commits globally.

---

## 📁 Repository Commands
- **`git init`**  
  📂 Initializes a new Git repository in the current directory.  
- **`git clone <repository_url>`**  
  🖨️ Creates a copy of an existing repository.

---

## ✅ Basic Commands
- **`git status`**  
  🔍 Displays the current state of the working directory and staging area.  
- **`git add <file>`**  
  ➕ Adds a specific file to the staging area.  
- **`git add .`**  
  ➕ Adds all changes in the working directory to the staging area.  
- **`git commit -m "message"`**  
  📝 Commits the staged changes with a message.  
- **`git log`**  
  📜 Shows a log of all commits in the repository.  
- **`git log --oneline`**  
  📜 Displays a compact, one-line log of commits.

---

## 🌳 Branch Management
- **`git branch`**  
  🌿 Lists all local branches.  
- **`git branch <branch_name>`**  
  🌿 Creates a new branch.  
- **`git checkout <branch_name>`**  
  🔀 Switches to the specified branch.  
- **`git checkout -b <branch_name>`**  
  🔀 Creates and switches to a new branch.  
- **`git merge <branch_name>`**  
  🔗 Merges the specified branch into the current branch.  
- **`git branch -d <branch_name>`**  
  ❌ Deletes a branch locally.

---

## 🌐 Remote Repository Commands
- **`git remote add origin <url>`**  
  🌎 Links a local repository to a remote repository.  
- **`git push origin <branch_name>`**  
  ⬆️ Pushes changes from the local branch to the remote repository.  
- **`git pull origin <branch_name>`**  
  ⬇️ Fetches and integrates changes from the remote branch.  
- **`git fetch`**  
  🔄 Downloads objects and refs from another repository.

---

## 🛠️ Staging and Changes
- **`git diff`**  
  🧐 Shows differences between the working directory and staging area.  
- **`git diff --staged`**  
  🧐 Displays differences between the staging area and the last commit.  
- **`git reset <file>`**  
  🧹 Removes a file from the staging area.  
- **`git reset --hard <commit_hash>`**  
  🔄 Resets the working directory and staging area to the specified commit.

---

## 🏷️ Tagging
- **`git tag <tag_name>`**  
  🏷️ Creates a tag for the current commit.  
- **`git tag`**  
  📋 Lists all tags.  
- **`git push origin <tag_name>`**  
  ⬆️ Pushes a tag to the remote repository.

---

## 🔄 Undoing Changes
- **`git restore <file>`**  
  🚫 Discards changes in the working directory for a specific file.  
- **`git restore --staged <file>`**  
  🚫 Removes a file from the staging area but retains changes in the working directory.  
- **`git revert <commit_hash>`**  
  🕒 Creates a new commit that undoes changes from a specific commit.

---

## 🔧 Advanced Commands
- **`git stash`**  
  📥 Temporarily stores changes in a dirty working directory.  
- **`git stash apply`**  
  📤 Applies the most recent stashed changes.  
- **`git rebase <branch_name>`**  
  🔄 Reapplies commits on top of another base branch.  
- **`git cherry-pick <commit_hash>`**  
  🍒 Applies the changes from a specific commit to the current branch.  
- **`git bisect`**  
  🔍 Performs a binary search to find a commit that introduced a bug.

---

## 🕵️‍♂️ Logs and History
- **`git show <commit_hash>`**  
  📜 Displays detailed information about a specific commit.  
- **`git blame <file>`**  
  🔎 Shows who modified each line of a file and when.