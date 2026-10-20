# GM Plast – Kontrolkort Online (PWA)

Static, browser-based demo with installable PWA files.

## Files
- `index.html` — form and interface
- `manifest.webmanifest` — PWA install metadata
- `sw.js` — offline app-shell cache
- `assets/icon-192.png`, `assets/icon-512.png` — app icons

## Run locally
Service workers require HTTPS or localhost. Open this folder with a local static server, for example VS Code Live Server, or use:
`python -m http.server 8080`
Then visit `http://localhost:8080`.

## Publish
Upload the contents of this folder to a static HTTPS host such as GitHub Pages. The PWA install prompt is controlled by the browser and may require the user to choose “Install app” / “Add to Home Screen”.

## Demo data
The form contains demonstration records. Saving stores data in this browser's local storage; it is not connected to a company database or ERP.
