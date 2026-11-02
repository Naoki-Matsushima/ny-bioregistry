# New York Bio-Based Stakeholder Registry

A research prototype from the Dynamic Sustainability Lab (DSL), Syracuse University. It lists growers, producers and consumers of sustainable aviation fuel, mass timber, bioplastics and biofuels in New York, merged from public databases. Every entry links back to the source record it came from.

**Open the registry:** see the website link in this repository's About box, or open `index.html` in any web browser.

## What is on the page

- **Map** (opens first): stakeholders per county; zoom in or click a county bubble to see each stakeholder
- **Stakeholders**: searchable list with filters and the source records behind each entry
- **Databases**: the 15 public databases reviewed and which ones are merged
- **How it works**: method, evidence levels and known gaps

Link to a tab directly by adding `#map`, `#stakeholders`, `#databases` or `#method` to the address.

## Data

669 stakeholders built from 698 records in six public databases (DOE Alternative Fueling Station Locator, EPA ECHO, USAspending.gov, FAA enplanements, NYS wood products directory, USDA BioPreferred), with county boundaries from the U.S. Census Bureau. Data retrieved 2026-10-26.

Entries marked **Inferred** were assigned by a rule or an AI first pass; check the original record before relying on them. Public data only; no personal contact details.

## Technical notes

`index.html` is a single self-contained file: the data, county boundaries and the Leaflet 1.9.4 map library (BSD-2-Clause, https://leafletjs.com) are embedded, so it works offline. Only the web fonts load from Google Fonts, and the page falls back to system fonts without them.

## Contact

Naoki Matsushima, Research Fellow, Dynamic Sustainability Lab, Maxwell School, Syracuse University
