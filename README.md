# Follow the Money: The Great Reshuffling

Interactive visualization of U.S. internal migration patterns, showing where 6.5 million American households moved in 2021-2022 and the $558 billion in taxable income that changed addresses.

## Live Demo

[View the visualization](https://YOUR_USERNAME.github.io/follow-the-money/)

## Features

- **Scrollytelling narrative** - Guided story revealing migration patterns step by step
- **Interactive arc map** - deck.gl powered WebGL visualization of migration flows
- **Choropleth underlay** - County-level net migration (green = gaining, red = losing)
- **Find Your County** - Geolocation-powered county finder with:
  - Mini-map showing county location
  - Percentile rankings vs. national averages
  - Auto-generated narrative about your county's migration story
  - Top origins and destinations lists
  - Similar counties recommendations
- **Chord diagram** - Shows flow relationships for selected county
- **Keyboard navigation** - Arrow keys, number keys, accessibility support

## Data Source

IRS Statistics of Income (SOI) County-to-County Migration Data, 2021-2022

## Tech Stack

- [deck.gl](https://deck.gl) - WebGL-powered map layers
- [MapLibre GL JS](https://maplibre.org) - Free map rendering
- [D3.js v7](https://d3js.org) - Data visualization
- [Scrollama](https://github.com/russellgoldenberg/scrollama) - Scroll-triggered events

## Files

- `scrollytelling.html` - Main visualization (self-contained)
- `flows_top1000.json` - Top 1,000 migration corridors
- `county_stats.json` - County-level migration statistics
- `us-counties.json` - US county boundaries (GeoJSON)
- `summary.json` - Summary statistics

## License

MIT
