# PUBG Mortar Distance Calculator v2026 - web calculator 2026

> **Browser-based PUBG mortar distance calculator for quick targeting checks.** This HTML/JavaScript web utility lets players measure map spans, adjust the view, and work with mortar aiming in the current 2026 release.

[![Platform](https://img.shields.io/badge/Platform-HTML%2FJavaScript-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bakerevan/pubg-mortar-map-distance-tool?style=flat-square)](https://github.com/bakerevan/pubg-mortar-map-distance-tool)

---

<p align="center">
  <a href="https://bakerevan.github.io/pubg-mortar-map-distance-tool/">
    <img src="https://img.shields.io/badge/Download-PUBG%20Mortar%20Distance%20Calculator%20Latest-brightgreen?style=for-the-badge" alt="Download PUBG Mortar Distance Calculator">
  </a>
</p>

> **[Download Latest Build](https://bakerevan.github.io/pubg-mortar-map-distance-tool/)**

---

[Download Latest Build](https://bakerevan.github.io/pubg-mortar-map-distance-tool/)

---

## Overview

PUBG Mortar Distance Calculator is a lightweight browser tool for checking map distances and planning mortar shots. The workflow stays simple: select a map, inspect the terrain, and use the interactive controls to estimate range with minimal manual work.

It is built for fast access in the browser, so it suits players who want a convenient reference while preparing or testing. With multi-language support and map-focused controls, the interface stays practical for repeated use without requiring a desktop installation.

---

## What it offers

- Interactive distance measurement for map-based planning
- Map selection for working across different layouts
- Mouse wheel zoom for close inspection and broad overview
- Drag panning for moving around the map view
- Grid toggles to help align measurements
- Kilometer labels for clearer distance reading
- Multi-language interface support
- Browser-based web tool with no local app install required

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/bakerevan/pubg-mortar-map-distance-tool.git
2. Open the project folder and host the HTML files with any static web server, or place it on GitHub Pages.
3. Launch the main page in a browser to start using the calculator.

If you are testing locally, open the root `index.html` file through a local server rather than a direct file path when possible.

---

## How to use it

Typical workflow:

1. Open the calculator in a browser.
2. Pick the map you want to measure.
3. Zoom with the mouse wheel to focus on a region.
4. Drag the view to reposition the map.
5. Turn grid overlays on or off when you need better alignment.
6. Read the kilometer markers and measure the distance you need.

Example setup for local preview:

- Start a simple static server
- Visit the local address in your browser
- Switch language or map as needed
- Use the distance view for target planning

---

## Configuration

Most settings are controlled from the web interface. For deeper customization, inspect the HTML and JavaScript files that define the map assets, labels, and language strings.

Common settings to look for:

- Map list definitions
- Grid display options
- Distance labels
- Language resource entries

Example structure:

{
  "map": "selected-map-name",
  "grid": true,
  "labels": "km",
  "language": "en"
}

---

## Requirements

- A modern web browser
- HTML and JavaScript support enabled
- A static hosting setup for GitHub Pages or local preview
- Enough screen space for map navigation and measurement work

---

## FAQ

**How do I run it online?**  
Host the project on GitHub Pages or another static web host, then open the published URL.

**Can I change the language?**  
Yes. The project includes multi-language support, so language options are managed through the interface or source files.

**Where are map and display settings stored?**  
They are typically defined in the HTML and JavaScript files that drive the calculator.

**The map is hard to inspect. What should I try?**  
Use zoom and drag panning together, and enable grid lines if you need more precise alignment.

**Is there a desktop installer?**  
No desktop installer is indicated in the project profile. It is presented as a web tool.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
