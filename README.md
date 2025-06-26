
# GitHub-for-Beginners (Admin-Focused Edition) 🚀

## 📅 Duration
**1 Week Intensive Track**

## 🎯 Goal
Master Git & GitHub (CLI + Desktop) with real projects, team workflows, GitHub Pages, and core administrative tools.

---

## 🗺️ Weekly Milestones

- ✅ Polished GitHub Profile + README
- ✅ 5+ pushed projects via GitHub CLI or Desktop
- ✅ Hosted portfolio on GitHub Pages
- ✅ Daily commit activity + green contribution graph
- ✅ Admin features: Branch protection, Teams, Permissions, 2FA
- ✅ Hands-on with Issues, Projects, Wiki, Actions

---

## 📆 Daily Breakdown

### 🟩 Day 1: Setup & GitHub Desktop
- Install Git and GitHub Desktop
- Configure Git globally
- Create repos, commit, and push via Desktop & CLI
- Use `.gitignore`

**Learning Goals**: Install & configure Git/GitHub, push projects using Desktop

🔍 What to search:

    how to install Git and GitHub Desktop on Windows/Linux/Mac

    how to configure global Git username and email

    how to create a GitHub repo and push code using GitHub Desktop

    how to push code using Git CLI

    what is .gitignore and how to use it in a Python project

    basic Git commands for beginners

**🔧 Mini Task**: 

- Install [GitHub Desktop](https://desktop.github.com/download/) on your Computer
  
- Install [Notepad++](https://notepad-plus-plus.org/downloads/) on your Computer
- Create a Repository on GitHub with README.md

- Clone Your created Repository on your Computer using GitHub Desktop.  
 
- Change the Something in README.md File using Notepad++ and Push the Changes to GitHub using GitHub Desktop   

---

### 🟦 Day 2: Branching & Collaboration
- Create/switch/merge branches
- Fork, clone, pull request
- Write Markdown-rich READMEs
- Add collaborators

**Learning Goals**: Understand branching, forking, pull requests, Markdown

🔍 What to search:

    how to create and switch branches in Git

    how to merge branches using Git CLI or GitHub

    what is forking in GitHub and how to use it

    how to create a pull request on GitHub

    how to write a professional GitHub README using Markdown

    how to add collaborators to a GitHub repo

**🔧 Mini Project**: Portfolio repo with `main` and `dev` branches  

🔍 What to search:

    how to create a personal portfolio on GitHub

    GitHub branching strategy for beginners
---

### 🟨 Day 3: Issues, Wiki, Projects, Actions
- Open/manage Issues with labels
- Use GitHub Projects (Kanban)
- Create GitHub Wiki
- Set up basic GitHub Actions

**Learning Goals**: Manage issues, use GitHub Projects, write documentation, explore GitHub Actions

🔍 What to search:

    how to create and manage GitHub Issues with labels

    how to use GitHub Projects for task management

    how to create a GitHub Wiki for documentation

    how to set up GitHub Actions for Python

    how to write unit tests in Python with unittest

    what is CI/CD with GitHub Actions  

**🔧 Mini Project**: CLI Network Scanner + Wiki + Issues

🔍 What to search:

    Python CLI network scanner tutorial

    how to document a Python project on GitHub using Wiki
---

### 🟧 Day 4: GitHub Pages & Profile
- Create Profile README
- Host portfolio using GitHub Pages
- Star/fork trending projects
- Learn commit streak tips

**Learning Goals**: Build GitHub profile, host portfolio using GitHub Pages

🔍 What to search:

    how to create a GitHub Profile README

    how to host a website using GitHub Pages

    GitHub Pages for HTML/CSS portfolio

    how to maintain GitHub commit streak

    how to fork and star trending repositories

**🛠️ Final Project**: Live GitHub Pages portfolio + Profile README + 3–5 projects

🔍 What to search:

    examples of GitHub Profile README for developers

    GitHub Pages portfolio templates for developers
    
---

## 📚 Practice Tools (Free & Online)

| Tool | Purpose | Link |
|------|---------|------|
| GitHub Learning Lab | Interactive GitHub practice | https://lab.github.com |
| Git-it | Beginner Git/GitHub challenges | https://github.com/jlord/git-it-electron |
| Markdown Live Preview | Live Markdown editor | https://markdownlivepreview.com |
| GitHub Pages Playground | Static site preview | https://pages.github.com |
| Git CLI Simulator | Practice Git commands in-browser | https://learngitbranching.js.org |
| Regexr | Useful for writing `.gitignore` rules | https://regexr.com |
| Codepen | Preview HTML/CSS for portfolio | https://codepen.io |
| Actions Playground | Sample GitHub Actions | https://github.com/actions/starter-workflows |
| Notepad++ | Source code editor and Notepad  | https://notepad-plus-plus.org/downloads/ |
| Visual Studio Code | Integrated Development Environment (IDE)   | https://code.visualstudio.com/ |

---

## 🔐 Admin Features

| Feature | How to Access | Why It Matters |
|--------|---------------|----------------|
| Add Collaborators | Repo > Settings > Collaborators | Manage access |
| Create Teams | Org > Teams | Group permissions |
| Branch Protection | Settings > Branches > Rules | Protect main |
| Require 2FA | Org > Settings > Authentication | Improve security |
| Audit Log | Org > Settings > Audit Log | Track activity |
| Dependabot | Security > Alerts | Fix vulnerabilities |

---

## 🛠️ GitHub Actions: Sample Python Workflow

```yaml
# .github/workflows/main.yml
name: Python CI

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-python@v4
        with:
          python-version: 3.9
      - run: pip install -r requirements.txt
      - run: python -m unittest
```

---

## 🌐 GitHub Pages Hosting

1. Add `index.html` to your repo
2. Go to `Settings > Pages`
3. Choose main branch
4. Access via: `https://username.github.io/repo-name`

---

## 🎯 Final Checklist

- ✅ GitHub Profile README
- ✅ GitHub Pages Portfolio
- ✅ 5+ Repositories with README & screenshots
- ✅ 1+ Repo with GitHub Actions
- ✅ Internal Wiki documentation
- ✅ Daily contributions (green squares)
- ✅ Admin knowledge: Teams, Rules, 2FA, Audit Logs
- ✅ CLI & GitHub Desktop fluency

---

## 🚀 Keep Practicing!
Continue learning through:
- [GitHub Skills](https://github.com/skills)
- [Open Source Contributions](https://opensource.guide/how-to-contribute/)
- [Hacktoberfest](https://hacktoberfest.com/)
