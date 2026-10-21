CHRISTIAN MAROWSKI — COMPLETE WEBSITE UPDATE (21 OCT 2026)

This ZIP contains the ENTIRE website, not just the changed files.
Upload the contents of the unzipped folder, not the ZIP itself.

CHANGES
- Homepage (index.html + stylesheet.css): centers the portrait and
  Education/Experience together inside a narrower 940px container.
  Left-aligned labels, portrait, blue lines, navigation and text styling stay.
- Publications (research.html): adds project website and Google Drive
  supporting-materials links directly beneath the multi-robot authoring paper.
- All five HTML pages: canonical internal links use one new version value
  (?v=20261021-centered-v3); the CSS link also uses this value to minimize
  stale browser cache displays after you replace your repository files.
- Homepage: reloads on return from browser back/forward cache, to avoid
  showing a previously saved snapshot after navigating between pages.

WHY OLD VERSIONS MAY REAPPEAR
An earlier issue was numbered file uploads: index(8).html does NOT replace
index.html, and projects(5).html does NOT replace projects.html.
GitHub Pages can also deploy from a different branch or folder, or retain
old browser/CDN cache temporarily. HTML cannot override a wrong publishing
source or older content deployed by another workflow.

HOW TO UPLOAD CORRECTLY
1. Unzip the package on your computer.
2. In GitHub, check Settings > Pages for the CURRENT publishing source,
   including the branch and folder (repository root or /docs).
3. Upload ALL files INSIDE this folder to that publishing folder.
   The landing page MUST literally be named index.html.
   Keep the website_images folder and filenames unchanged.
4. Replace each existing index.html, research.html, projects.html,
   gnn-flocking.html, cv.html and stylesheet.css; do not upload numbered
   copies such as index(9).html or another nested folder.
5. Commit the changes. In Actions, check that a GitHub Pages deployment
   completes from the expected commit. If multiple workflows publish the
   same site, investigate which source is configured; don't delete one
   just because a previous version appeared.
6. Visit both the site root (/) and /index.html and check both show the
   centered homepage. If not, see which exact branch/folder is published.
7. If needed, hard refresh (Ctrl+Shift+R) or try a private window.

This package does not modify your GitHub repository automatically.
