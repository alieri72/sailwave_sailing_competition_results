# Sailing Results HTML Generator

This project retrieves official sailing race results published in Sailwave format and automatically generates a clean, static HTML report with consolidated classifications.

## Features

- Scrapes official Sailwave result tables directly from the event website
- Supports multiple competitions (ILCA 4 and ILCA 6, but can be changed )
- Preserves original official tables for reference
- Computes:
  - Individual rankings by division (age category)
  - Individual rankings by yacht club
  - Collective club rankings (Top N sailors per club)
  - Overall club ranking across competitions
- Highlights Top 3 positions visually
- Generates a single navigable HTML page with internal links
- Uses an external CSS stylesheet for easy customization
- Output is fully static and works offline

## Output

The generated HTML file is saved to the `output/` directory:

