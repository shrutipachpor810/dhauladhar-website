# Dhauladhar Website

A responsive static website for Dhauladhar Alternative Assets & Investments.

## Technologies

- **HTML5** for the page structure and content.
- **CSS3** for styling, responsive layouts, light and dark themes, and reduced-motion support. Styles are embedded in `index.html`.
- **Vanilla JavaScript** for navigation, the mobile menu, theme selection, the disclaimer dialog, scroll progress, and reveal animations. Scripts are embedded in `index.html`.
- **Google Fonts**: Inter and Newsreader, loaded from Google Fonts when a network connection is available. System fonts are used as fallbacks.
- Image assets remain in `images/` for reference, but the website currently displays no images and does not load those files.

There is no framework, package manager, or build step. This is a static site.

## Project structure

```text
.
├── index.html       # Site markup, styles, and JavaScript
├── README.md        # Project and setup notes
└── images/          # Logos, illustrations, and team photos
```

## Preview locally

Open `index.html` in a browser, or serve the folder over HTTP. For example, with Python installed:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy

Upload the project files to any static web host. For Netlify, connect the GitHub repository and use the repository root as the publish directory; no build command is needed.

## Updating the site

Edit the content and embedded CSS or JavaScript in `index.html`. Commit and push changes to the connected Git branch to trigger a deployment when continuous deployment is configured.
