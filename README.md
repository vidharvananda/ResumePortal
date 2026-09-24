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

GitHub Pages deployment is configured in `.github/workflows/deploy-pages.yml`.
In the repository, open **Settings → Pages** and set the publishing source to
**GitHub Actions**. The workflow deploys the portal on every push to `main`.
For this repository, the site URL is:
https://vidharvananda.github.io/ResumePortal/

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
