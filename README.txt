CHRISTIAN MAROWSKI — WEBSITE (CORRECTED LINKS + PROJECT LABELS)

Why it was switching back to old pages
----------------------------------
Your uploaded copies had numbered names (index(8).html, projects(5).html,
gnn-flocking(1).html, stylesheet(8).css). However, the website navigation
always links to index.html, projects.html, and gnn-flocking.html.
If the numbered copies were uploaded to the repo without renaming them, the
original pages would remain unchanged and navigation would show older content.
Browser/CDN cache can also briefly serve older content after a deployment.

What this package changes
-------------------------
- Files are named using the CORRECT canonical names with no (1), (5), (8).
- Every page's internal links and stylesheet reference have the same version
  query (?v=20261021-canonical-v2) to force a fresh request after deployment.
- Projects listing no longer has the `Graph Neural Networks · Imitation Learning`
  eyebrow above the project title; keeps `Class Project · Multi-Robot Systems`
  below the title.
- GNN detail page removes the topic eyebrow above the title and shows
  `Class Project · Multi-Robot Systems` directly BELOW the title.
- Existing layout, navigation style, results, embedded videos, and photos
  remain unchanged.

Exact GitHub Pages steps
------------------------
1. EXTRACT this ZIP on your computer. Do not upload the ZIP directly.
2. On GitHub, open your site's PUBLISHING folder (normally repository root,
   or /docs if Settings > Pages says /docs).
3. Upload ALL files FROM INSIDE the extracted folder, not the outer folder.
   When GitHub shows the upload, it should say files such as index.html,
   projects.html, gnn-flocking.html, stylesheet.css, and website_images/... .
4. Confirm the upload will REPLACE the original index.html, projects.html,
   gnn-flocking.html etc. Numbered copies are NOT replacements.
5. Delete any accidental duplicate numbered filenames (index(8).html etc.)
   in the repository if you want to keep it tidy; do NOT delete canonical files.
6. Commit to the branch configured in Settings > Pages and check the published
   site after the deployment is green.
7. For stale browser pages, try Ctrl+Shift+R or a private/incognito window.
   The ?v= query in the navigation and stylesheet is meant to avoid stale
   browser caches.

Reminder: GitHub Pages default workflows should not be deleted.

Images must live in website_images (underscore), not `website images`.
