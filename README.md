# Aadipranav S – Portfolio

Static portfolio site (no build step). Files:

- `index.html` – the whole site (HTML, CSS, JS, photo)
- `intro.mp4` – 5-second welcome video that plays when the site opens

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000

## Push to GitHub
1. Create an empty repo on GitHub (no README, no .gitignore), e.g. `aadipranav-portfolio`.
2. In this folder:

    git init
    git add .
    git commit -m "Initial portfolio"
    git branch -M main
    git remote add origin https://github.com/Aadi6777/aadipranav-portfolio.git
    git push -u origin main

## Deploy on Vercel
1. Go to vercel.com, sign in with GitHub, choose Add New > Project, import the repo.
2. Framework Preset: Other. Leave Build Command and Output Directory empty.
3. Click Deploy. You get a free `*.vercel.app` link, and every `git push` redeploys.

## Change the intro video
Replace `intro.mp4` with a new file of the same name (keep it under a few MB), commit and push.
