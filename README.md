# Kadam Vishwa Teja - Portfolio

A single-page portfolio built with React, Tailwind CSS, GSAP and three.js (all loaded from CDNs, so no install is needed).

## Run on your computer
1. Unzip this folder.
2. Double-click `index.html`. It opens in your browser (internet needed for fonts and libraries).

Optional local server (PowerShell, inside this folder):
    npx serve .

## Edit your content
Open `index.html` in VS Code and search for:
- `var projects=[` : project titles, descriptions, tags and links
  Set `liveUrl` and `repoUrl` for each project. A link button appears only when the URL is not empty.
  Projects with no links show "In progress".
- `var skills=[` : skill groups
- `var EMAIL=` and `var GH=` : contact details

## Deploy free
Vercel: push this folder to a GitHub repo, then Import it on vercel.com (no build settings needed).
Netlify: drag this folder onto app.netlify.com/drop.
GitHub Pages: push to a repo, then Settings > Pages > deploy from the main branch.
