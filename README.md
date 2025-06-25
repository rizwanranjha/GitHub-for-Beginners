
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

**🔧 Mini Project**: Push a Python To-Do App

---

### 🟦 Day 2: Branching & Collaboration
- Create/switch/merge branches
- Fork, clone, pull request
- Write Markdown-rich READMEs
- Add collaborators

**🔧 Mini Project**: Portfolio repo with `main` and `dev` branches

---

### 🟨 Day 3: Issues, Wiki, Projects, Actions
- Open/manage Issues with labels
- Use GitHub Projects (Kanban)
- Create GitHub Wiki
- Set up basic GitHub Actions

**🔧 Mini Project**: CLI Network Scanner + Wiki + Issues

---

### 🟧 Day 4: GitHub Pages & Profile
- Create Profile README
- Host portfolio using GitHub Pages
- Star/fork trending projects
- Learn commit streak tips

**🛠️ Final Project**: Live GitHub Pages portfolio + Profile README + 3–5 projects

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
