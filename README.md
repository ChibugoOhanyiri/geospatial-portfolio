# Geospatial Portfolio

Chibugo Ohanyiri's geospatial, remote-sensing and Earth-observation work, from field survey and GIS analysis to satellite remote sensing. Code projects have their own repositories (linked here as sub-repositories under `published/`); earlier GIS projects are written up as case studies under `case-studies/`.

| Project | What it does | Links |
|---|---|---|
| **Lekki flood radar evidence (STAC Environmental Processor)**<br>Personal project · 2026 | Turns Sentinel-1 radar from the 30 June 2026 Lagos flood into reproducible evidence: aligned imagery with receipts, control days, a practice/test split, a STAC catalogue and a clickable map. | [Repository](https://github.com/ChibugoOhanyiri/stac-environmental-processor) · [Live map](https://chibugoohanyiri.github.io/stac-environmental-processor/) · [Report](https://github.com/ChibugoOhanyiri/stac-environmental-processor/blob/main/REPORT.md) |
| **3D flood-inundation visualisation, Rivers State, Nigeria**<br>Individual project · Nov 2023 | 3D terrain model showing exposure to hypothetical water-level rise, told as a StoryMap. 🏆 Second runner-up, GIS Day Nigeria StoryMap Competition. | [Case study](case-studies/rivers-state-3d-flood-inundation/) |
| **Topographic mapping of the Digital Library, UNIZIK**<br>Group project · 2023 | DGPS/GNSS field survey, SRTM and Kriging in ArcGIS for a topographic map with contours, spot heights, buildings and roads. | [Case study](case-studies/unizik-digital-library-topographic-map/) |
| **Ozone concentrations, California, USA**<br>Personal project · 2023 | Interpolated monitoring-station ozone, summarised by census tract and elevation zone, and related to household income and elevation. | [Case study](case-studies/california-ozone-spatial-analysis/) |
| **Parcel and terrain analysis, Valmeyer, Illinois, USA**<br>Personal project · 2024 | Parcel-level elevation and slope of a town relocated after flooding, with an interactive web map of parcels, roads and terrain. | [Case study](case-studies/valmeyer-parcel-terrain-analysis/) |
| **Land surface temperature, Osaka, Japan**<br>Personal project · 2024 | Landsat 8 thermal imagery processed with the Single-Channel Algorithm to map urban surface heat against development and population. | [Case study](case-studies/osaka-land-surface-temperature/) |
| **Proposition 37 voting patterns, California, USA**<br>Personal project · 2023 | Precinct results aggregated to county "Yes" shares and mapped with Jenks Natural Breaks. | [Case study](case-studies/california-prop-37-voting-patterns/) |


## Working with this repository
Clone everything at once:
```text
git clone --recurse-submodules https://github.com/ChibugoOhanyiri/geospatial-portfolio.git
```
After committing inside a project, record its new version here:
```text
git add <project-folder>
git commit -m "Update <project> to latest"
git push
```

Built with AI assistance (Claude); each project records which decisions and work were the author's own.
