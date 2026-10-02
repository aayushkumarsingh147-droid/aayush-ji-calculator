# Aayush Ji Calculator

A small, installable calculator for desktop and mobile browsers. The standalone `index.html` download also works offline without installing an app.

## Try it locally

Open `index.html` to use the calculator or test the standalone download. To test browser installation and offline caching, serve this folder from `localhost` (for example, run `python -m http.server 8000` in this directory and visit `http://localhost:8000`).

## Install on a device

- **Windows:** Open the hosted site in Microsoft Edge or Google Chrome and use the browser's install option. Or download `index.html` and open it in a browser.
- **Android:** Open the hosted site in Chrome, open the menu, then choose **Install app** or **Add to Home screen**.
- **iPhone or iPad:** Open the hosted site in Safari, tap **Share**, then **Add to Home Screen**.

The installable website requires HTTPS when hosted. The standalone HTML file does not.

## Publish

Upload the complete contents of this folder to a static website host that serves HTTPS, such as GitHub Pages, Netlify, or Cloudflare Pages. Keep `index.html`, `manifest.webmanifest`, `sw.js`, and `icon.svg` together at the same site path. After deployment, share the website URL; visitors can install the app or download the standalone HTML from the page.
