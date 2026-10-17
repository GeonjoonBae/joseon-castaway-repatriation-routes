# Data sources and interpretation

## Historical route evidence

The reconstructed postal-station sequences draw primarily on the "Relay Itineraries" in the *Huidian zeli* and on itinerary evidence discussed in the associated article and appendices. The public GeoJSON files retain only short source summaries; detailed textual criticism remains in the article.

## CHGIS

Historical administrative boundaries, lakes, administrative-seat coordinates where identified, and the DEM-hillshade background derive from the China Historical Geographic Information System (CHGIS). The map distinguishes administrative-seat proxies from exact station-site identifications where the available evidence permits.

Suggested citation:

> CHGIS, Version 6. Cambridge, MA: Harvard Yenching Institute and Fudan Center for Historical Geography, 2016.

The DEM-hillshade tiles used by the viewer derive from the project CHGIS Version 5 DEM layer, based on GTOPO-30.

## Other cartographic sources

The Figure 3 waterway reconstruction uses a Natural Earth Yangtze centreline together with the project Grand Canal reference geometry. Natural Earth data are available at <https://www.naturalearthdata.com/>.

## DEM candidate routes

The separately named DEM-hybrid layers use the Copernicus DEM GLO-30 Public 2021 digital surface model, downloaded from the Registry of Open Data on AWS. The 30 m source tiles were resampled to a 90 m working grid and evaluated with a slope-only anisotropic least-cost model equivalent to the GRASS `r.walk` walking-cost equation.

Copernicus DEM source and documentation:

- <https://registry.opendata.aws/copernicus-dem/>
- <https://copernicus-dem-30m.s3.amazonaws.com/readme.html>

The DEM output is a first-pass terrain-accessibility candidate. It does not by itself identify a Qing postal road and has not been promoted to a source-corroborated route geometry.

## Accuracy statement

- Route lines are generalized analytical connections.
- They do not reproduce the exact historical road or travelled alignment unless explicitly stated.
- Some station points use historical administrative seats as spatial proxies.
- Coordinate confidence and coordinate basis are retained in public popups when available.
- Figure 4's corridor band expresses a shared transport corridor rather than a measurable road width.
- DEM-hybrid layers model terrain accessibility and remain separate from the publication geometry pending hydrographic and historical-source review.
