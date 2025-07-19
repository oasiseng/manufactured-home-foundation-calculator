# Manufactured Home Foundation Calculator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/manufactured-home-foundation-calculator.svg?style=social)](https://github.com/yourusername/manufactured-home-foundation-calculator/stargazers)

A simple, web-based tool to estimate foundation sizes, piers, tie-down spacing, and material costs for manufactured home foundations based on the HUD Permanent Foundations Guide for Manufactured Housing (PFGMH, HUD 7584). This calculator helps users get quick HUD-compliant estimates incorporating factors like soil bearing capacity, wind zones, and seismic adjustments.

**Note:** This is an estimation tool for educational purposes. Always consult a licensed engineer for actual designs and certifications. Costs are rough material estimates; labor and regional variations are not included.

## Features

- **Input Parameters:**
  - Home width (ft: 12, 14, 16, 18, 20, 24, 28)
  - Foundation type (Footing with Masonry Blocks or Cast-in-Place Piers)
  - Soil type (Bearing capacity in psf: Clay 1500, Sandy 2000, Loamy 2500, Gravel 3000)
  - Wind zone (I: 110 mph, II: 120 mph, III: 130 mph)
  - Seismic zone (Low: no adjustment, Medium: -1 ft spacing, High: -2 ft spacing)
  - Home length (ft: 10-100)
  - Optional: Include engineer inspection estimate ($450)

- **Outputs:**
  - Foundation dimensions (piers count, footing/pier sizes, spacing)
  - Tie-down requirements (anchors count, spacing, type)
  - Estimated material costs (foundation, tie-downs, total; optional inspection)
  - Compliance note with link to schedule professional inspection
  - Illustrative image of a manufactured home foundation

- **Reference Tables:** Results presented in structured tables for clarity.
- **Responsive Design:** Works on desktop and mobile with tooltips for guidance.
- **No Dependencies:** Pure HTML, CSS, and JavaScript—runs in any modern browser.

## Demo

You can try the calculator live [here](https://oasisengineering.com/manufactured-home-foundation-calculator/).

## Installation

No installation required! This is a static web page.

1. Clone the repository:
