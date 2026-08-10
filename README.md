# Somers Point Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Somers Point municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01411320, Ocean City
- PETSS / NOAA station: 8534975
- NAVD88 thresholds: 3.27 ft minor, 4.27 ft moderate, 5.27 ft major
- MLLW thresholds: 5.3 ft minor, 6.3 ft moderate, 7.3 ft major
- MLLW = NAVD88 + 2.03 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Somers Point boundary at 5-foot resolution.
