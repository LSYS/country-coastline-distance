## Cross-country coastline data
List of countries (and territories) with area and coastline distance data.
  
| Variable               | Description                                                                                                                                              |
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|
| country           | Country Name                                                                                                                                             |
| iso2              | ISO 3166 Alpha-2 country codes                                                                                                                           |
| area_wf           | Country area (sq km) from *The World Factbook* (area compares the sum of all land and water areas delimited by international boundaries and/or coastlines) |
| coastline_wf      | Coastline distance (km) from *The World Factbook* (length of the boundary between the land area, including islands, and the sea)                          |
| coast_to_area_wf  | (coastline_wf / area_wf) * 100                                                                                                                           |
| coastline_wri     | Coastline distance (km) from *World Resources Institute*                                                                                                 |
| coast_to_area_wri | (coastline_wri / area_wf) * 100                                                                                                                          |

#### Data sources
* coastline_wf (https://www.cia.gov/library/publications/resources/the-world-factbook/fields/282.html)
* area_wf (https://www.cia.gov/library/publications/the-world-factbook/fields/279rank.html)
* coastline_wri (https://web.archive.org/web/20120419075053/http://earthtrends.wri.org/text/coastal-marine/variable-61.html)

#### Usage notes
* Country codes (ISO-3166, e.g. EE) should be the ```main key``` rather than country name (e.g. Estonia)
* Some country name entries are outdated (e.g. Swaziland now Eswatini, SZ). Country codes are more reliable