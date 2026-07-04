# D-Lux 8 Settings Advisor

A single-page web app that recommends Leica D-Lux 8 camera settings based on location, light, subject, and desired look — with saved camera profiles and a "copy prompt for Claude" tab for open-ended questions.

It's a self-contained static app: all HTML, CSS, and JS live in `index.html`, and profile data persists in the browser's `localStorage`. No build step, no dependencies.

## Running locally

Open `index.html` directly in a browser, or serve the directory with any static file server, e.g.:

```
npx serve .
```

## Deploying

This repo is served directly by GitHub Pages from the `index.html` at the root — no build step. Live at:

https://euanm55.github.io/d-lux-8/
