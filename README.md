# All We Are Impact Map

Interactive Mapbox visualization built by Sean Ryan for **All We Are** to make the nonprofit's solar installation data in Uganda easier to explore.

## Project status

This repository is a **snapshot of the version I built in 2026**. Ongoing use and maintenance have since been handed off to the All We Are team.

The CSV and GitHub Pages version preserved here should be treated as a portfolio/archive copy of that work, **not as the current authoritative All We Are dataset**. The original internal master spreadsheet is no longer linked from this repository.

## What it does

The map turns installation records into interactive geographic features. Users can:

- browse project sites across Uganda
- jump to a site with the selector
- explore clustered locations
- click sites for installation details
- switch map styles

## How it works

The project uses:

- **Mapbox GL JS** for the interactive map, clustering, navigation, and popups
- **D3** to load and parse the CSV data
- a bundled CSV export so this archived version remains reproducible

The snapshot data used by the map is stored in:

`Impact_Map_Export - System Bridge (Anchor point).csv`

## Live snapshot

https://strokeofluck.github.io/all-we-are-map-box/

---

Created by Sean Ryan for All We Are.
