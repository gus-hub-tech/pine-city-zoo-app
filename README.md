# Pine City Zoo — Static Web App

A lightweight, static website that presents Pine City Zoo content (exhibits, animals, places, and visitor info). The project is built with plain HTML and CSS and is ready to run as a static site (locally or via GitHub Pages).

## Project Overview
This repository contains a multi-page static site that showcases animals, attractions, and visitor features for Pine City Zoo. Each animal and place has its own dedicated HTML page with detailed information and images. The site features a central map-based navigation system and organized content sections.

## Key Features
- Interactive map-based home page (index.html)
- Dedicated animal pages with detailed descriptions and images
- Places section featuring attractions, dining, and entertainment venues
- Weather information page
- Visitor feedback system with confirmation page
- Centralized stylesheet for consistent visual design
- Organized image assets with categorized subdirectories
- Navigation system with top and bottom tab bars

## Tech Stack
- HTML5 — site structure and content
- CSS3 — styling and layout

## Repository Structure

### Main Pages
- `index.html` — Home page with interactive zoo map
- `animals.html` — Animal directory with navigation to individual animal pages
- `places.html` — Places directory with links to attractions and facilities
- `weather.html` — Current weather information
- `feedback.html` — Visitor feedback form
- `message-recieved.html` — Feedback submission confirmation page

### Animal Pages
- `elephant.html` — African Elephant exhibit
- `gemsbok.html` — Gemsbok antelope exhibit
- `giraffe.html` — Giraffe exhibit
- `gorilla.html` — Gorilla habitat
- `koala.html` — Koala enclosure
- `lion.html` — Lion exhibit
- `monkey.html` — Monkey habitat
- `panda.html` — Giant Panda exhibit
- `warthog.html` — Warthog exhibit

### Places & Attractions
- `amphitheatre.html` — Educational shows and entertainment venue
- `insecthouse.html` — Insect discovery center
- `monkeytrail.html` — Interactive monkey trail experience
- `forest.html` — Lost Forest nature walk
- `coffeeshop.html` — Coffee shop and refreshments
- `mopizza.html` — Mos Pizza restaurant
- `dinezoo.html` — Dine Zoo main restaurant

### Assets & Documentation
- `style.css` — Main stylesheet for the entire site
- `images/` — Image assets organized by category:
  - `animal-images/` — Animal photographs and thumbnails
  - `places-images/` — Attraction and facility images
  - `weather-images/` — Weather-related icons and backgrounds
  - Root level: logos, maps, navigation elements
- `pinecityzoo-documents/` — Project documentation and content files
- `README.md` — This documentation file

## How to Run Locally
Because the site is static, you can open it directly in a browser or serve it with a simple static server.

### Option 1 — Direct Browser Access
1. Clone or download the repository
2. Navigate to the project directory
3. Open `index.html` in your web browser

### Option 2 — Local Server (Recommended)
Using a local server ensures proper loading of assets and relative paths.

**Python 3:**
```bash
cd pine-city-zoo-app3
python -m http.server 8000
```
Then open http://localhost:8000 in your browser

**Node.js (http-server):**
```bash
npm install -g http-server
cd pine-city-zoo-app3
http-server
```
Open the displayed local URL in your browser

### Option 3 — VS Code Live Server
- Install the Live Server extension
- Right-click on `index.html` and select "Open with Live Server"
- Enjoy auto-reload functionality during development

## Deployment
This static site is ready for deployment on various hosting platforms:

### GitHub Pages
1. Enable Pages in repository settings
2. Set source to main branch (root directory)
3. Site will be available at `https://username.github.io/repository-name`

### Netlify
- Drag and drop the project folder to Netlify
- Or connect via Git for automatic deployments

### Vercel
- Import the repository
- Deploy as a static site with zero configuration

### Other Static Hosts
Compatible with any static hosting service including AWS S3, Firebase Hosting, or traditional web hosting.

## Current Features

### Navigation
- Consistent top navigation: Animals, Map, Places
- Bottom navigation: Weather, Feedback
- Interactive map on home page
- Thumbnail-based browsing for animals and places

### Content Organization
- 9 detailed animal exhibits with descriptions and images
- 7 places including dining, entertainment, and attractions
- Weather information system
- Visitor feedback collection

### Visual Design
- Centralized CSS styling in `style.css`
- Consistent layout across all pages
- Image thumbnails with navigation arrows
- Organized image assets by category

## Potential Improvements

### Accessibility & SEO
- Add alt attributes to all images for screen readers
- Implement semantic HTML elements (header, main, nav, footer)
- Add meta tags for viewport, description, and social sharing
- Include ARIA landmarks and keyboard navigation support

### Performance
- Optimize and compress images
- Consider WebP format for better compression
- Implement lazy loading for images
- Add favicon and consistent meta tags

### Functionality
- JavaScript enhancements for form validation
- Active navigation state highlighting
- Search/filter functionality for animals and places
- Interactive map features

### Development
- Convert to static site generator (Jekyll, Eleventy) for easier maintenance
- Add automated testing (Lighthouse CI)
- Implement responsive design improvements
- Add build process for asset optimization

## Project Structure Details

### Image Organization
```
images/
├── animal-images/          # Animal photos and thumbnails
├── places-images/          # Attraction and facility images
├── weather-images/         # Weather icons and backgrounds
├── logo.png               # Site logo
├── map.png                # Interactive zoo map
├── next-arrow.png         # Navigation elements
└── [animal]-tn.png        # Animal thumbnail images
```

### Documentation
The `pinecityzoo-documents/` folder contains:
- Animal link descriptions
- Animal page content guidelines
- Places link descriptions
- Places page information templates

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit with clear messages (`git commit -m 'Add accessibility improvements'`)
5. Push to your branch (`git push origin feature/improvement`)
6. Open a Pull Request with a detailed description

### Suggested Contributions
- Accessibility improvements (alt text, semantic HTML)
- Mobile responsiveness enhancements
- Performance optimizations
- Interactive features with JavaScript
- Content updates and corrections


## Contact
For questions, suggestions, or collaboration opportunities, please open an issue in the repository or contact the project maintainer.

---

*Pine City Zoo Static Web App - A demonstration project showcasing static site development with HTML and CSS.*

## Demo

https://github.com/user-attachments/assets/a3678735-8a76-4615-ab92-679754f1eec0


