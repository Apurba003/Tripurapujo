# Tripura Pujo Guide

A mobile-first Tripura Durga Puja discovery guide built as a standalone HTML app.

## Run locally

Open `index.html` directly in a browser, or serve the folder with:

```powershell
python -m http.server 4173
```

Then visit `http://127.0.0.1:4173/`.

## Included

- City- and district-wise pandal discovery across Tripura's eight districts
- Search, district/city/theme/status filters, and crowd-pattern estimates
- Interactive map with city-to-city route estimates, a keyless Google Maps preview, and live Google Maps route links
- Trip planner with car, bike, bus/transit, walk, and train guidance
- Persistent add-to-plan and visited tracking using browser local storage
- Self-service missing-puja entry and public-listing email request
- English, Bangla, Hindi, light-by-default theme support with a persisted Light/Dark toggle, and responsive mobile layout

The guide starts in the light theme regardless of the device colour preference. Use the **Dark theme** / **Light theme** button in the header to switch themes; the selected theme is saved in `localStorage` for that browser.

Distances, train details, and crowd levels are estimates. Confirm live route, timings, traffic restrictions, and local club information before travelling.

The map preview uses Google's keyless `output=embed` URL with the selected city or pandal coordinates. No Google Maps API key is stored or required; route buttons open Google Maps for live navigation, traffic, and alternate routes.
