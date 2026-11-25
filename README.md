# QuietSpot · Smart Library Noise Monitor

QuietSpot is a student proof-of-concept for making noise activity visible in shared library spaces. This repository contains a single-page interactive concept site and a compact browser-rendered 3D enclosure model.

## Demo features

- Three-zone dashboard with illustrative sample readings and an activity chart.
- Optional browser microphone input. Audio is analyzed locally in the page and is not recorded or uploaded.
- Drag-to-rotate enclosure model with cutaway, exploded, labels, and reset controls.
- Responsive layout for desktop and mobile.

## Important prototype status

The dashboard slider and sample chart are simulated. Microphone mode displays a relative browser audio activity index, not calibrated decibels (dB). No ESP32 hardware is connected to this site. The device layout is conceptual and not a manufacturing drawing. A real deployment would need sensor firmware, calibration, a data endpoint, and testing with library users.

## Run locally

Open `index.html` in a modern browser. Microphone access requires a secure context (HTTPS or localhost) and is optional.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the repository root to GitHub Pages whenever a change is pushed to `main`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions** if Pages is not already enabled.

