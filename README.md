# lukebuddie.github.io

Personal portfolio website for Luke Buddie — Economics at UC Berkeley, finance & strategy.

## Live Site
→ https://lukebuddie.github.io

---

## Deploying to GitHub Pages

### Step 1 — Create the repository
1. Go to github.com and sign in
2. Click **New repository**
3. Name it exactly: `lukebuddie.github.io`
4. Set to **Public**
5. Click **Create repository**

### Step 2 — Upload the files
Option A — GitHub web UI (easiest):
1. Open your new repo
2. Click **Add file → Upload files**
3. Drag the entire contents of this folder (all files and subdirectories)
4. Click **Commit changes**

Option B — Git CLI:
```bash
cd lukebuddie.github.io
git init
git remote add origin https://github.com/lukebuddie/lukebuddie.github.io.git
git add .
git commit -m "Initial site launch"
git push -u origin main
```

### Step 3 — Enable GitHub Pages (auto for username repos)
For a repo named `username.github.io`, GitHub Pages is automatically enabled.
Your site will be live at **https://lukebuddie.github.io** within 1–2 minutes.

---

## File Structure

```
lukebuddie.github.io/
├── index.html                     ← Main site (edit this to update content)
├── style.css                      ← All styling
├── README.md
├── assets/
│   ├── img/
│   │   └── headshot.jpg           ← Your photo
│   └── Luke_Buddie_Resume.pdf     ← Your resume
└── files/
    ├── business-pitches/          ← Playmaker, Nike, Shake Shack, JOOCE
    ├── corporate-finance/         ← Element Bar, Lululemon, Hanson, Jones, OptiGuard, Cavalier
    ├── financial-models/          ← Kroger, Lululemon, Panera, Williams-Sonoma, JOOCE
    └── economics/                 ← Salmon, Econ 140, Kahneman, Econ 100B, Ordeals
```

---

## Updating the site

**Add a project:** Copy an existing `<div class="project-card">` block in `index.html`,
update the title, description, tags, and file path in the `href` of the download link.

**Add a file:** Drop the new file in the relevant `files/` subfolder and push to GitHub.

**Update your bio or resume:** Edit the relevant section in `index.html` and replace
`assets/Luke_Buddie_Resume.pdf` with the new file.

---

## Contact
lukebuddie04@gmail.com
