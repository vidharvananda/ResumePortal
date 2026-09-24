# Vidharva Nanda — Career Portal

A self-contained, single-file resume dashboard website. No build tools, no
dependencies, no internet required (fonts fall back gracefully if offline).

## Files
- index.html — the complete portal (HTML + CSS + JavaScript in one file)
- README.md — this file

## View it locally
Just double-click index.html, or right-click → Open With → your browser.
Everything works offline except Google Fonts, which fall back to system fonts.

## Deploy it (make it a public URL)

Option A — GitHub Pages (free, ~5 minutes)
1. Create a GitHub account / log in at https://github.com
2. Click "New repository" → name it e.g. "resume-portal" → set it Public → Create
3. Click "uploading an existing file" and drag in BOTH files (or use git):
   git clone https://github.com/<your-username>/resume-portal.git
   cp index.html README.md resume-portal/
   cd resume-portal && git add . && git commit -m "Add resume portal" && git push
4. Repo Settings → Pages → Source: "Deploy from a branch" → Branch: main, folder: / (root) → Save
5. Your site goes live at https://<your-username>.github.io/resume-portal/

Option B — Netlify Drop (fastest, no account needed to start)
1. Go to https://app.netlify.com/drop
2. Drag the unzipped folder onto the page
3. You instantly get a live URL you can share (custom name available)

Option C — Any web host
Upload both files to your web root. That's it — there is nothing else to install.

## Customize
Open index.html in any text editor. All content lives in clearly-marked
sections (OVERVIEW, IMPACT METRICS, EXPERIENCE, SKILLS, AWARDS, EDUCATION,
CONTACT). Colors and fonts are defined once at the top in the :root CSS
variables — change e.g. --navy or --accent to re-theme the whole portal.

Contact details, metric values, and skill bars are plain text in the HTML,
so they can be edited without touching the code logic.
