# Rhyne Route — standalone website

This folder is the complete site. Keep all four files together:

- `index.html` — the page
- `rr-catalog.js`, `rr-courses.js`, `rr-data.js` — course and program data

## Put it online (free, ~2 minutes)

**Option A — Netlify Drop (easiest, no account setup needed to try)**
1. Go to https://app.netlify.com/drop
2. Drag this whole `rhyne-route` folder onto the page.
3. You get a live link like `https://something.netlify.app`. Sign in to keep it and rename it (e.g. `rhyne-route.netlify.app`).

**Option B — GitHub Pages**
1. Create a new public repository (e.g. `rhyne-route`) on github.com.
2. Upload the four files (Add file → Upload files) and commit.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)` → Save.
4. Your site appears at `https://<your-username>.github.io/rhyne-route/` within a minute or two.

**Option C — Vercel or Cloudflare Pages**: create a new project, upload/import the folder, no build settings needed (it's plain HTML).

## Try it on your computer first
Double-click `index.html`, or for the most accurate test run
`python3 -m http.server` inside this folder and open http://localhost:8000.

## What changed from the Claude version
- "Copy share link" and the advisor summary now link to wherever you host the site.
- "Save backup file" and "Save as PDF" download files normally in the browser.
- The **Ask AI** tab needs Claude's runtime, so on your own site it shows a note pointing to the Claude version. Everything else works the same.
- Saved plans, grades and themes are stored in each visitor's own browser (localStorage).

## Custom domain
Netlify, GitHub Pages, Vercel and Cloudflare all let you attach a domain you buy (e.g. `rhyneroute.com`) in their settings.

Note: the site is labeled unofficial. If you publish it publicly, keep that label and avoid Lenoir-Rhyne logos unless the university approves.
