# 🤖 AI/ML Portfolio — GitHub Pages

A clean, dark-themed portfolio site for showcasing AI/ML projects, hosted on GitHub Pages.

## 🚀 Live Site

👉 `https://YOUR_USERNAME.github.io`

---

## 📁 Repo Structure

```
YOUR_USERNAME.github.io/
├── index.html          ← Main portfolio page (edit this)
├── README.md           ← This file
└── projects/           ← (Optional) individual project detail pages
```

---

## ✏️ How to Customize

### 1. Update your name & links
Open `index.html` and find/replace:
- `YOUR_USERNAME` → your GitHub username
- `YOUR_NAME` → your display name
- `YOUR_HANDLE` → your LinkedIn / Twitter handle
- `you@email.com` → your email

### 2. Add your projects
Each project card looks like this — duplicate and fill in your real projects:

```html
<a href="https://github.com/YOUR_USERNAME/your-repo" class="project-card" style="--card-accent: var(--nlp)">
  <span class="card-arrow">→</span>
  <div class="card-category">NLP / LLM</div>
  <div class="card-title">Your Project Title</div>
  <div class="card-desc">What does it do? What problem does it solve? 2–3 lines.</div>
  <div class="card-tags">
    <span class="tag">Python</span>
    <span class="tag">PyTorch</span>
  </div>
</a>
```

**Category color variables:**
| Category | CSS Variable |
|---|---|
| NLP / LLM | `var(--nlp)` → cyan |
| Generative AI | `var(--gen)` → purple |
| Reinforcement Learning | `var(--rl)` → amber |
| Classical ML | `var(--ml)` → green |

### 3. Update your tech stack
In the Skills section, edit the `<span class="pill">` items to match your actual stack.

---

## 🌐 Deploying to GitHub Pages

### Step 1 — Create the repo
Name it exactly: `YOUR_USERNAME.github.io`

```bash
git init
git add .
git commit -m "initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

### Step 2 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `root`
4. Click **Save**

Your site will be live at `https://YOUR_USERNAME.github.io` in ~1 minute.

---

## 📦 Individual Project Repos

Each AI/ML project should have its own repo with a strong README. Template:

```markdown
# Project Title

> One-line description of what this does.

## Overview
What problem does it solve? Why does it matter?

## Results
- Metric 1: XX%
- Metric 2: XX

## Quick Start
\`\`\`bash
pip install -r requirements.txt
python train.py
\`\`\`

## Approach
Brief explanation of the model/algorithm used.

## Demo
Link to notebook / Hugging Face Space / demo video
```

---

## 💡 Tips

- Pin your best project repos on your GitHub profile
- Add a `demo.gif` or screenshot to each project README
- Host model demos on [Hugging Face Spaces](https://huggingface.co/spaces) (free)
- Use [nbviewer](https://nbviewer.org/) to share notebooks with rendered outputs
