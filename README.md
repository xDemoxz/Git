🚀 Git Essentials Cheat Sheet

A quick reference guide for the most important Git commands to manage repositories, configure credentials, and push your projects using Visual Studio or any terminal.

🔧 1. Initial Setup & Credentials

Set your global username and email (required before making commits):

git config --global user.name "Your Name"
git config --global user.email "your@email.com"

Check your configuration:

git config --list
🔑 Change or Reset Credentials (Windows - Visual Studio)

If you need to update credentials:

Open Credential Manager
Go to Windows Credentials
Remove Git-related entries (GitHub, etc.)
Re-authenticate on next push
📁 2. Create or Connect to a Repository
Initialize a new repo:
git init
Connect to a remote repo:
git remote add origin https://github.com/username/repo.git

Verify remote:

git remote -v
📦 3. Basic Workflow (Add, Commit, Push)
Add files:
git add .
Commit changes:
git commit -m "Your commit message"
Push to GitHub:
git push -u origin main
🔄 4. Sync Changes

Pull latest changes:

git pull origin main
🧹 5. Reset & Undo Changes
Unstage files:
git reset
Reset last commit (keep changes):
git reset --soft HEAD~1
Reset everything (⚠️ deletes changes):
git reset --hard
🌿 6. Branching

Create new branch:

git checkout -b new-branch

Switch branch:

git checkout main
✅ 7. Helpful Tips
Always pull before pushing to avoid conflicts
Write clear commit messages
Use branches for new features
Avoid --hard reset unless necessary
📌 Quick Flow
git init
git add .
git commit -m "first commit"
git remote add origin <repo-url>
git push -u origin main
