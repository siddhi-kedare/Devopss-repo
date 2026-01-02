# git installation
apt-get install git

# Check git
git --version

# Configure user
git config --global user.name "Your Name"
git config --global user.email "your-email@gmail.com"

# Check config
git config --list

git clone https://github.com/USERNAME/my-project.git
cd my-project

# Check Status & Branch
git status
git branch

# Create new branch and loging
git checkout -b feature-login 
        OR 
git switch -c feature-login

# Commit Changes
git commit -m "Add login feature UI"

# Push Feature Branch to GitHub
git push origin feature-login


# Update Local main Branch
git checkout main
git pull origin main

# For delete
local: git branch -d feature-login
remote: git push origin --delete feature-login

# Check version
git --version


