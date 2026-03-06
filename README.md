# Sudharshan Rao Allu — Academic Portfolio

Professional portfolio site for recruiters and resume sharing. Hosted on **GitHub Pages** (like [raghuhemadri.github.io](https://raghuhemadri.github.io/)).

## Host on GitHub Pages

### Option A: Your portfolio at `https://<username>.github.io/`

1. Create a **new repository** on GitHub named **exactly** `AlluSudharshanRao.github.io` (replace with your GitHub username).
2. Clone it and add your site files:
   ```bash
   git clone https://github.com/AlluSudharshanRao/AlluSudharshanRao.github.io.git
   cd AlluSudharshanRao.github.io
   ```
3. Copy into this folder: `index.html`, `styles.css`, `script.js`, `.nojekyll`, and any assets.
4. Commit and push:
   ```bash
   git add .
   git commit -m "Portfolio site"
   git push -u origin main
   ```
5. On GitHub: **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** → Folder: **/ (root)** → Save.
6. After a minute or two, your site will be live at **https://AlluSudharshanRao.github.io**.

### Option B: Your portfolio at `https://<username>.github.io/Portifolio/`

1. Create a repository named **Portifolio** (or any name) on GitHub.
2. Push this project folder to that repo (`main` branch, root of repo).
3. **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** → Folder: **/ (root)** → Save.
4. Site will be at **https://AlluSudharshanRao.github.io/Portifolio/**.

Use **Option A** if you want a clean URL like [raghuhemadri.github.io](https://raghuhemadri.github.io/).

## Run locally

- Open `index.html` in a browser, or run a local server:
  - **Python:** `python -m http.server 8000` → http://localhost:8000
  - **Node:** `npx serve .`

## Contents

- **About** — Summary, focus areas, Summer 2026 internship interest  
- **Experience** — NYU Secure Systems Lab, NIT Sikkim, Zessta, Intellithink, Evercons  
- **Projects** — MLOps recommendation system, RAG document assistant, IDS, and more  
- **Education** — NYU Tandon (MS), NIT Sikkim (BTech)  
- **Skills** — ML, LLM/RAG, PyTorch, FastAPI, Docker, etc.  
- **Publications** — SDN load balancing, Alzheimer’s detection  
- **Certifications** — Data Science, NLP, GenAI  
- **Volunteer** — HESS at NYU  
- **Contact** — Email, phone, LinkedIn, GitHub  

## Files

- `index.html` — Structure and content  
- `styles.css` — Layout, typography, responsive and print styles  
- `script.js` — Mobile menu, footer year, scroll behavior  
- `.nojekyll` — Tells GitHub Pages to serve the site as static files (no Jekyll).  

No build step or dependencies; works with any static host.
