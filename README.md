# trees-mapnik

[Mapnik][mapnik-website] style definitions to generate street trees map tiles in multiple zoom levels.

- [Mapnik style documentation][mapnix-style-docs].
- The map tiles are generated based on data retrieved from a PostgreSQL/PostGIS database. The configuration (database name, table name) is part of the style definiton in the XML.


## Related data set

- [Baumbestand Berlin][fis-broker-berlin-street-trees] (Anlagenbäume, Strassenbäume)


## Spatial reference system

- [EPSG-25833][espg-25833-spatialreference]: used in Berlin, Germany
- [EPSG-4326][espg-4326-spatialreference]: used by OpenStreetMap, Google Maps, Leaflet.js, ...


[espg-25833-spatialreference]: http://spatialreference.org/ref/epsg/etrs89-utm-zone-33n/
[espg-4326-spatialreference]: http://spatialreference.org/ref/epsg/wgs-84/
[fis-broker-berlin-street-trees]: http://fbinter.stadt-berlin.de/fb/index.jsp?loginkey=zoomStart&mapId=k_wfs_baumbestand@senstadt
[mapnik-website]: http://mapnik.org
[mapnix-style-docs]: https://github.com/mapnik/mapnik/wiki/XMLConfigReference#style
