# Overview
Group activity to familiarize with git for today

# Commands
1. `git init` - initializes a git repository
2. `git status` - shows changes made to repository, categorised by tracked/untracked.
3. `git diff` - shows the diff
4. `git add <filename>` - add new new
5. `git reset <filename>`
6. `git commit -m "<descriptive message>"`
7. `git log`
8. `git branch <branch name>`
9. `git checkout <branch name>`
10. `git merge <branch name>`
11. `git branch -d <branch name>`

# Code Contributors
- peh3
- tklearning1983 

# …or create a new repository on the command line
echo "# coaching14" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/peh3/coaching14.git
git push -u origin main

# …or push an existing repository from the command line
git remote add origin https://github.com/peh3/coaching14.git
git branch -M main
git push -u origin main
