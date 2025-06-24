# 🚀     GitHub-for-Beginners

**Duration:** 1 Week  
**Goal:** Master Git & GitHub with practical projects and a professional GitHub profile

---

## 🗺️ Overview

By the end of this week, You will have:

- ✅ A polished GitHub profile with a Profile README
- ✅ 5+ pushed projects (Python/web/CLI)
- ✅ Hosted portfolio on GitHub Pages
- ✅ Hands-on experience with GitHub Issues, Wiki, Projects, Actions
- ✅ Solid understanding of Git commands and workflows
- ✅ Daily contributions on GitHub

---

## 📆 Daily Schedule

### 🟩 **Day 1: Git & GitHub Basics**

#### Topics:
- Git installation & config
- GitHub account creation
- Creating repositories (public/private)
- Local repo setup, staging, commit, push
- `.gitignore` usage

#### Mini Project:
- Push a Python script (e.g., To-Do App or Calculator)

---

### 🟦 **Day 2: Branching, Markdown & Collaboration**

#### Topics:
- Branching: `git branch`, `checkout`, `merge`
- Writing effective `README.md`
- Markdown formatting
- Forking, Pull Requests, Collaborators

#### Mini Project:
- Student Portfolio repo with `main` and `dev` branches

---

### 🟨 **Day 3: Issues, Projects, Wiki, Actions**

#### Topics:
- Creating and managing GitHub Issues
- Setting up a Project Kanban board
- Writing a Wiki (IT/Support Notes)
- Intro to GitHub Actions (CI with Python)

#### Mini Project:
- CLI Network Scanner App + Issues + Wiki

---

### 🟧 **Day 4: GitHub Pages & Profile Optimization**

#### Topics:
- Creating GitHub Profile README
- Hosting a portfolio with GitHub Pages
- Exploring, starring, and forking projects
- Building commit streaks (green graph!)

#### Final Project:
- Hosted portfolio + Profile README + 3–5 projects

---

## 🛠️ Git & GitHub How-To Guides

### ✅ Setup & Account

```bash
# Install Git: https://git-scm.com/downloads

# Configure Git
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Create GitHub account: https://github.com

✅ Repository Management

# Create a repo on GitHub: https://github.com/new

# Clone a repo
git clone https://github.com/username/repo-name.git

# Initialize local repo
git init

# Add and commit changes
git add .
git commit -m "Initial commit"

# Link to GitHub repo and push
git remote add origin https://github.com/username/repo.git
git push -u origin main

🔐 Public vs Private Repositories

    To create private/public repo: Select visibility when creating at https://github.com/new

    To change visibility: Go to repo > Settings > Danger Zone > Change Visibility

✅ Branching & Collaboration

# Create and switch to a new branch
git checkout -b dev

# Merge branch into main
git checkout main
git merge dev

# Delete a branch
git branch -d dev

    Add collaborator: Repo > Settings > Collaborators > Add by username

    Create Pull Request: Fork → Make changes → Click “Pull Request”

✅ Writing Markdown & README

# Project Title
## Description
## Installation
## Usage
## Screenshots
## Contributing
## License

    Live preview: https://markdownlivepreview.com

✅ .gitignore

# Create a .gitignore file
touch .gitignore

# Common patterns
__pycache__/
.env
*.log
node_modules/

Generate from: https://www.toptal.com/developers/gitignore
✅ GitHub Features
🐞 GitHub Issues

    Go to Issues tab → New Issue → Add details & labels

✅ GitHub Projects (Kanban)

    Projects tab → New Project → Use Board template

📚 GitHub Wiki

    Wiki tab → Create first page → Write IT Notes/Guides

✅ GitHub Actions (CI/CD)

# .github/workflows/main.yml
name: Python CI

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Set up Python
        uses: actions/setup-python@v4
        with:
          python-version: 3.9
      - name: Install dependencies
        run: pip install -r requirements.txt
      - name: Run tests
        run: python -m unittest

✅ GitHub Pages & Profile
🌐 Host a static site:

    Create repo with HTML or Markdown content

    Go to Settings > Pages

    Source: main branch, root

    Access: https://username.github.io/repo-name

👤 Profile README:

    Create a repo named exactly like your GitHub username

    Add README.md — it will appear on your profile

✅ Build Your Contribution Graph

# Daily commit example
echo "update log" >> daily.txt
git add .
git commit -m "Daily update"
git push

    Contribute at least 3× per week to stay green!

    Fork and explore repos at: https://github.com/explore

✅ Final Deliverables

Profile README

GitHub Pages portfolio

5+ repositories (with README, screenshots)

1 repo using GitHub Actions

IT Documentation Wiki

Consistent commit history
