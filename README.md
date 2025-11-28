# Pine City Zoo — Static Web App

A lightweight, static website that presents Pine City Zoo content (exhibits, animals, places, and visitor info). The project is built with plain HTML and CSS and is ready to run as a static site (locally or via GitHub Pages).

## Project overview
This repository contains a multi-page static site that showcases animals, attractions, and visitor features for a fictional or demo zoo called Pine City Zoo. Each animal or place has its own HTML page. There is a central stylesheet and an images directory for assets. A simple contact/feedback flow is provided with a feedback page and a "message received" page.

## Key features
- Multi-page static website (each animal/attraction has a dedicated page)
- Centralized stylesheet (style.css) for visual consistency
- Simple feedback/contact flow
- Image assets stored in images/ directory
- Organized, easy-to-edit HTML files suitable for demos, prototypes, or teaching static-site basics

## Tech stack
- HTML5 — site structure and content
- CSS3 — styling and layout

## Repository file map (high-level)
Files and folders present in the repository (representative list):
- index.html — Home / entry page
- style.css — Main stylesheet for the site
- animals.html — List or index of animals
- places.html — List or index of places/attractions
- feedback.html — Visitor feedback/contact form page
- message-recieved.html — Confirmation page after feedback submission
- animal-specific pages: amphitheatre.html, elephant.html, giraffe.html, gorilla.html, gems bok.html, koala.html, lion.html, panda.html, monkey.html, warthog.html, etc.
- insecthouse.html, monkeytrail.html, coffeeshop.html, mopizza.html, dinezoo.html, weather.html — other attraction/utility pages
- images/ — directory containing image assets
- pinecityzoo-documents/ — documents folder (empty or for related docs)
- README.md — this file

(See repository root for the complete list of HTML pages — each animal and many attractions have their own file.)

## How to run locally
Because the site is static, you can open it directly in a browser or serve it with a simple static server.

Option 1 — Open locally
1. Clone the repo:
   git clone https://github.com/gus-hub-tech/pine-city-zoo-app.git
2. Open index.html in your browser.

Option 2 — Serve with a simple local server (recommended for relative asset paths)
- Python 3:
  1. cd pine-city-zoo-app
  2. python -m http.server 8000
  3. Open http://localhost:8000 in your browser
- Node (http-server):
  1. npm install -g http-server
  2. http-server
  3. Open the shown local URL

Option 3 — VS Code
- Use the Live Server extension to preview and auto-reload.

## Deployment
This is ready to host on static hosting platforms:
- GitHub Pages: Enable Pages in repository settings and point to the main branch (root).
- Netlify/Vercel: Drag-and-drop the repo or connect via Git, and deploy as a static site.

## Accessibility, SEO, and optimization notes
- Ensure all images in /images have descriptive alt attributes for accessibility.
- Use semantic HTML elements (header, main, nav, footer, figure) if not already present to improve accessibility and SEO.
- Consider optimizing images (compressing and using modern formats like WebP) to reduce page load size.
- Add meta tags (viewport, description, social) for better mobile behavior and discoverability.
- Add landmarks, keyboard navigation, and ARIA where appropriate.

## Recommended improvements
- Add a small JavaScript layer to:
  - Validate or submit the feedback form (e.g., via a third-party form service or serverless function).
  - Enhance navigation (active link highlighting, search/filter animals).
  - Lazy-load images to improve performance.
- Convert repetitive HTML into templates or switch to a static site generator (Jekyll, Eleventy) if the number of pages grows.
- Add unit or visual tests (e.g., Lighthouse checks in CI) for performance/accessibility regression tracking.
- Add a favicon and consistent meta tags across pages.
- Add a LICENSE file to specify reuse terms.

## Contributing
- If you want to contribute, you can:
  - Fork the repository
  - Make changes on a feature branch
  - Open a pull request with a clear description of the change
- Suggested first contributions:
  - Improve accessibility (alt text, semantic tags)
  - Consolidate repeated markup into templates
  - Add responsive design improvements or mobile-first breakpoints



## License
No license file detected. Add a LICENSE to declare reuse terms (MIT, Apache 2.0, or another license as desired).

## Contact / Credits
- Repo owner: gus-hub-tech (they own the repository)
- For questions or collaboration, open an issue or contact the owner via their GitHub profile.

---

