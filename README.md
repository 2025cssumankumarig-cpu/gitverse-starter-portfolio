# 🚀 GitVerse Starter Portfolio Template

Welcome to **GitVerse** — the hands-on Git & GitHub competition organized by **Software Focus Group (SFG)**!

This repository is your starting template. Your goal is to fork this repository, customize it into your personal developer portfolio, make logical and incremental commits, automate deployment with GitHub Pages, and open a Pull Request back to the original repository.

---

## 📋 Competition Workflow: Step-by-Step

### Step 1: Fork This Repository
1. Click the **Fork** button (top-right of this page) to create your own copy under your personal GitHub account.
2. Uncheck *"Copy the main branch only"* if asked, and click **Create Fork**.

### Step 2: Clone to Your Local Machine
In your terminal (Git Bash / Linux terminal / macOS terminal):
```bash
git clone git@github.com:<YOUR_GITHUB_USERNAME>/gitverse-starter-portfolio.git
cd gitverse-starter-portfolio
```

### Step 3: Enable GitHub Pages in Your Fork
1. Go to your forked repository on GitHub $\rightarrow$ Click **Settings** (top tab).
2. In the left sidebar, click **Pages** (under *Code and automation*).
3. Under **Build and deployment > Source**, select: **GitHub Actions**!
   *(This allows `.github/workflows/deploy.yml` to automatically publish your site on push)*.

### Step 4: Customize Your Portfolio
Open the project in VS Code (`code .`):
* `index.html`: Update your name, role, bio, skills, and project descriptions.
* `css/style.css`: Customize colors (edit the CSS variables in `:root`), fonts, or card layouts.
* `js/main.js`: Update your email address and customize any interactive features.
* *AI Tools (ChatGPT, Claude, Gemini, Copilot) are 100% permitted to help write or refine code!*

### Step 5: Commit Incrementally
Do **not** make one giant commit called *"finished"*. Group your changes logically:
```bash
git add index.html
git commit -m "feat: customize hero section and bio"

git add css/style.css
git commit -m "style: update theme palette to cyberpunk neon"

git add js/main.js
git commit -m "feat: add personal email clipboard copy action"
```

### Step 6: Push to Your Fork
```bash
git push origin main
```
* Switch to the **Actions** tab on your GitHub repository.
* Watch the workflow run and turn **GREEN (✓)**!
* Your portfolio is now live at: `https://<YOUR_GITHUB_USERNAME>.github.io/gitverse-starter-portfolio/`!

### Step 7: Open a Pull Request (PR)
1. Go to your forked repository on GitHub.
2. Click **Contribute** $\rightarrow$ **Open Pull Request**.
3. Target:
   * **Base Repository:** `Original SFG Repository` | **Base Branch:** `main`
   * **Head Repository:** `Your Fork` | **Compare:** `main`
4. Fill in a descriptive PR Title (e.g., `Submission: Shreeram Hegde - Portfolio Showcase`).
5. In the PR description, include:
   * A summary of what you built/customized.
   * **Your Live GitHub Pages URL** (Test it first!).
   * Key features added.
6. Click **Create Pull Request**!

---

## 🏆 Evaluation Focus & Submission Rules

Evaluations are conducted directly through your **Pull Request (PR)** against this upstream repository.

### ⚠️ Critical Submission Requirements
1. **Pull Request Required:** If you do not open a Pull Request back to this repository, your project **cannot be evaluated**.
2. **PR Description:** You must include your **Live GitHub Pages URL** (verified working) and list all **Team Members (Names & USN)** in the description.
3. **Hard Deadline:** Only commits and Pull Requests registered **before the announced deadline timestamp** will be reviewed. Any late submissions will be disqualified.

### What the Judges Look For
* 🌿 **Git & Branch Hygiene:** Frequent conventional commits (`feat:`, `style:`, etc.), feature branching, and clean merge conflict resolution.
* 🌐 **Live Working Site:** Flawless GitHub Pages deployment with zero broken assets or 404 links.
* ⚙️ **CI/CD Pipeline:** Successful automated GitHub Actions workflow run deploying your site.
* 🤝 **Pull Request Quality:** Clear PR title, descriptive summary of changes, and clean diff.
* 🎨 **Originality & Execution:** Creative personalization, clean responsive layout, and distinct developer identity (AI tools are welcome!).

Good luck, and happy hacking! 🚀
