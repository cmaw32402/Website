CHRISTIAN MAROWSKI — ACADEMIC WEBSITE

WHAT CHANGED
- Kept the existing white-background, dark-blue styling and top navigation.
- Changed "Course Projects" in navigation to "Projects".
- Replaced the placeholder projects page with one GNN project.
- Added the detailed gnn-flocking.html page with project description,
  Webots setup image, comparison plots, metrics and two Google Drive demos.
- Updated the shared header name to Christian Marowski.

PUBLISH ON GITHUB PAGES
1. Extract this ZIP before uploading. A ZIP itself will NOT publish these pages.
2. Copy index.html, projects.html, gnn-flocking.html, research.html,
   cv.html, stylesheet.css and the website_images/ folder to the
   same directory in your GitHub Pages repository (normally its root).
3. Commit the changes on the branch configured in Settings > Pages.
4. Open https://YOUR-USERNAME.github.io/YOUR-REPO/projects.html
   (or https://YOUR-USERNAME.github.io/projects.html for a user site).
5. If a page appears stale, hard-refresh with Ctrl+Shift+R. In GitHub
   Actions, check the Pages deployment if it has not updated.

LOCAL PREVIEW
- Easiest: double-click index.html (or projects.html).
- For a web-server preview: open a terminal in this extracted folder and run:
    python -m http.server 8000
  Then open http://localhost:8000/projects.html.

FOLDER NAMES AND VIDEOS
- The image folder must be named EXACTLY website_images (underscore).
- The HTML references three project PNGs and IMG_9210.jpeg.
- Google Drive demos require viewer permissions that let others access them.
- This package leaves unfilled Education, Experience, About, Research,
  and CV placeholder text unchanged from the original template.

LATEST SMALL LAYOUT FIXES
- Home portrait begins level with the Education/Experience tabs.
- Project list thumbnail starts level with the GNN project title.
- The GNN detail page setup screenshot sits beside the page title instead of in Approach.
- Removed the extra topic labels above the GNN project titles.
