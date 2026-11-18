# RoadEye — AI Road Damage Detection & Smart Reporting

Minor project: a web app that detects road damage (potholes, cracks), rates severity, shows reports on a map (Leaflet + OpenStreetMap) and exports reports.

## Run

It is a single self-contained page — no build step.

- **Easiest:** double-click `index.html` to open it in a browser.
- **Local server (recommended):**
  ```bash
  python -m http.server 8000
  ```
  then open http://localhost:8000

Internet is needed for map tiles and Google Fonts.

## Android app (install on phone)

RoadEye is an installable PWA (manifest + service worker).

1. Open https://anushkashrivastava51.github.io/roadeye/ in **Chrome** on Android.
2. Menu (⋮) → **Add to Home screen / Install app** → Install.
3. Open **RoadEye** from the home screen — it runs full-screen like a native app, with camera and GPS access.

## Live (GitHub Pages)

Repo → Settings → Pages → Source: `main` branch, `/ (root)` → Save.
Site will be at `https://<username>.github.io/roadeye/`.
