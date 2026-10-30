# Dhauladhar Website

A responsive static website for Dhauladhar Alternative Assets & Investments.

## Technologies

- **HTML5** for the page structure and content.
- **CSS3** for styling, responsive layouts, light and dark themes, and reduced-motion support. Styles are embedded in `index.html`.
- **Vanilla JavaScript** for navigation, the mobile menu, theme selection, the disclaimer dialog, scroll progress, and reveal animations. Scripts are embedded in `index.html`.
- **Google Fonts**: Inter and Newsreader, loaded from Google Fonts when a network connection is available. System fonts are used as fallbacks.
- **PNG and JPEG images** stored locally in `images/`.

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

Upload the project files, including the complete `images/` folder, to any static web host. For Netlify, connect the GitHub repository and use the repository root as the publish directory; no build command is needed. Keep the relative `images/...` paths intact when deploying.

## Updating the site

Edit the content and embedded CSS or JavaScript in `index.html`. Keep image filenames and their paths in sync when replacing or adding assets. Commit and push changes to the connected Git branch to trigger a deployment when continuous deployment is configured.
