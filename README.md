# KalleMind Website

The marketing/landing website for KalleMind — a mobile health app for Zimbabwean users that helps people understand health information, prepare for healthcare conversations, and find qualified healthcare professionals.

## Structure

```
kallemind-website/
├── index.html      # The site itself (single-file, self-contained)
├── assets/         # Images, logos, etc. referenced by index.html
├── .gitignore
└── README.md
```

## Local development

Open this folder in VS Code and use the **Live Server** extension:

1. Right-click `index.html` in the Explorer panel.
2. Choose **"Open with Live Server"**.
3. The site opens in your browser and auto-refreshes on save.

No build step, no dependencies — it's plain HTML/CSS.

## Deploying

**Option A — GitHub Pages** (free, built into this repo)
1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Set Source to the `main` branch, `/ (root)` folder.
4. Save — GitHub gives you a live URL shortly after.

**Option B — Netlify**
- Drag and drop this folder onto [app.netlify.com](https://app.netlify.com), or connect this GitHub repo for auto-deploy on every push.

## Pushing changes

```bash
git add .
git commit -m "describe your change"
git push
```
