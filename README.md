# All We Are Impact Map

Interactive Mapbox visualization built by Sean Ryan for **All We Are** to make the nonprofit's solar installation data in Uganda easier to explore.

## Project status

This repository is a **snapshot of the version I built in 2026**. Ongoing use and maintenance have since been handed off to the All We Are team.

The CSV and GitHub Pages version preserved here should be treated as a portfolio/archive copy of that work, **not as the current authoritative All We Are dataset**. The original internal master spreadsheet is no longer linked from this repository.

## What it does

An interactive map of All We Are’s solar installations across Uganda. Visitors can search for a customer or site, explore clustered locations, switch map styles, and view installation details.

## How I built it

I combined the fields needed for the map from four existing spreadsheets into a read-only master sheet, leaving the organization’s source records unchanged.

The map uses **D3 to load a CSV export** and **Mapbox GL JS for mapping, clustering, navigation, and popups**. At handoff, the data could be updated by replacing the CSV. This repository preserves the last bundled export as a snapshot of the version I worked on.

## Live snapshot

https://strokeofluck.github.io/all-we-are-map-box/

---

Created by Sean Ryan for All We Are.
