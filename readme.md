# Perceptual Circle Scaling: U.S. COVID-19 Death Estimates (2022)

This interactive web map visualizes estimated COVID-19 death tolls across U.S. states for the year 2022 using perceptually scaled circle markers. Larger circles represent higher death estimates, while smaller circles represent lower totals. The map allows users to visually compare the spatial distribution and relative magnitude of COVID-19-related deaths by state.

## Features
- Circle markers sized using perceptual (square root) scaling.
- Hover interaction to highlight states.
- Tooltips displaying state name and death estimates.
- Dynamic legend showing minimum, median, and maximum values.
- Custom map tile styling and zoom/scale controls.

## Libraries Used
- [Leaflet.js](https://leafletjs.com/) for map rendering and interactivity.
- jQuery for loading GeoJSON data.
- Leaflet-AJAX for asynchronous data loading.

## Data Source
- CDC National Center for Health Statistics (NCHS):  
  [CDC COVID-19 Death Estimates](https://www.cdc.gov/nchs/pressroom/sosmap/covid19_mortality_final/COVID19.htm)

---

Created as part of a geographic data visualization lab assignment.
