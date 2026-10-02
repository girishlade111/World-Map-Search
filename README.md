# World Map Search

A lightweight, client-side world map search app built with Leaflet and OpenStreetMap. Search any place on earth, pan and zoom freely, and switch between map themes — all without a build step or API key.

## Features

- Place search powered by OpenStreetMap (Nominatim)
- Interactive Leaflet map — pan, zoom, markers
- Light/dark theme switcher
- Fully client-side — no API keys, no backend, no login
- Responsive layout for desktop and mobile

## Tech Stack

- HTML5 / CSS3
- Vanilla JavaScript
- [Leaflet.js](https://leafletjs.com) (map rendering)
- [OpenStreetMap](https://www.openstreetmap.org) tiles + Nominatim search
- Google Fonts (Roboto)

## Quick Start

No installation or build needed:

```bash
# open directly
open index.html

# or serve locally
npx serve .
```

## Project Structure

```
World-Map-Search/
├── index.html   # Full app — markup, styles, and map logic
├── README.md
└── LICENSE
```

## Deploy Notes

Plain static site (single `index.html`, no build step). Served from the repository root on GitHub Pages or any static host.

## Credit

Built by Girish Lade — https://ladestack.in
