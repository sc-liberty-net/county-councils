# South Carolina County Councils

An interactive map of South Carolina's 46 counties. Click a county to see its council
roster, its 2026 candidates, and the sources behind them.

**Live map: https://sc-liberty-net.github.io/county-councils/**

Counties without published research are drawn hatched and say so when clicked, so the
map states its own coverage rather than implying it is complete. Each county's panel
carries the date its research was checked.

## About the data

- **Council members and candidates** come from official county council directories and
  the South Carolina Election Commission candidate tracker at `vrems.scvotes.sc.gov`.
  Every county panel links to its own sources.
- **Candidate status is time-sensitive.** Check the official SC Elections tracker before
  relying on any candidate record here.
- **County boundaries** are US Census Bureau cartographic boundary files
  (`cb_2025_us_county_500k`), generalised for display. They are not authoritative for
  legal boundary questions.

## About this repository

This repository holds the built map only — one self-contained HTML file with no external
requests, no analytics, and no browser storage. It is generated from a separate research
and build pipeline and published here.

Corrections to any council record are welcome via an issue.
