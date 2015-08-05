# awesome geojson [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

GeoJSON utilities that will make your life easier.

### operations

* [geojson-coords](https://github.com/mapbox/geojson-coords): Extract coordinates from GeoJSON
* [geojson-extent](https://www.npmjs.com/package/geojson-extent): compute the bounding box of geojson features
* [geojson-flatten](https://github.com/mapbox/geojson-flatten): flatten multi geometries into normal geometries
* [geojson-js-utils](https://github.com/maxogden/geojson-js-utils): JavaScript helper functions for manipulating GeoJSON
* [geojson-merge](https://github.com/mapbox/geojson-merge): Merge multiple GeoJSON files into one FeatureCollection.
* [geojson-normalize](https://github.com/mapbox/geojson-normalize): normalize any geojson object into a geojson featurecollection
* [geojson-pick](https://www.npmjs.com/package/geojson-pick): remove all but specified properties from features in a geojson featurecollection
* [geojson-random](https://github.com/mapbox/geojson-random): generate random geojson points, lines, and polygons
* [geojson-rewind](https://github.com/mapbox/geojson-rewind): enforce ring winding order
* [geojson-summary](https://github.com/mapbox/geojson-summary): get a plain-english summary of what's in a geojson file
* [point-grouper](https://github.com/substack/point-grouper): group geojson points into containing polygons
* [geojson-join](https://github.com/tmcw/geojson-join): join geojson against json, dbf, and csv files
* [simplify-geojson](https://github.com/maxogden/simplify-geojson): apply the ramer-douglas-peucker line simplification to geojson features or feature collections in JS or on the CLI

### validation

* [geojsonhint](https://github.com/mapbox/geojsonhint): find errors in your geojson files

### services

* [geojsonio-cli](https://github.com/mapbox/geojsonio-cli): send geojson features to [geojson.io](http://geojson.io/) from your command line
* [geojsonio-extension](https://github.com/mapbox/geojsonio-extension): chrome extension for editing github files in geojson.io
* [geojsonlint](http://geojsonlint.com/): REST interface for GeoJSON validation
* [mapshaper](http://mapshaper.org/): Simple interface for simplification and conversion of GeoJSON and TopoJSON
* [koop](https://github.com/Esri/koop): Server that recuts Esri & GitHub services as GeoJSON endpoints

### conversion

* [csv2geojson](https://github.com/mapbox/csv2geojson): convert CSV to geojson
* [geojson-mapnikify](https://github.com/mapbox/geojson-mapnikify): Transform GeoJSON objects into Mapnik XML stylesheets with embedded GeoJSON data and simplestyle-spec-derived styles.
* [geojson-vt](https://github.com/mapbox/geojson-vt): Slice GeoJSON into vector tiles on the fly in the browser
* [geojson2dsv](https://github.com/mapbox/geojson2dsv): convert geojson to csv and tsv
* [geojson2rtree](https://github.com/maxogden/geojson2rtree): generate a static rtree (using terraformer) from a set of geojson features
* [ogr2ogr](http://www.gdal.org/ogr2ogr.html): convert anything to anything
  * [fiona](https://github.com/toblerity/fiona): nice python interface on top of ogr
* [minjur](https://github.com/mapbox/minjur): converts OpenStreetMap data to GeoJSON faster than anything else
* [shp2json](https://github.com/substack/shp2json): convert shapefile zip archives to streaming GeoJSON
* [togeojson](https://github.com/mapbox/togeojson): convert gpx & kml to geojson
* [tokml](https://github.com/mapbox/tokml): convert geojson to KML
* [topojson](https://github.com/mbostock/topojson): convert GeoJSON to & from TopoJSON, join data from CSV
* [vt-geojson](https://github.com/developmentseed/vt-geojson): Extract GeoJSON from Mapbox vector tiles
* [wellknown](https://github.com/mapbox/wellknown): convert wkt to geojson
* [osmtogeojson](https://github.com/tyrasd/osmtogeojson): convert OpenStreetMap data to GeoJSON
* [esri2open](https://github.com/project-open-data/esri2open) converts proprietary Esri formats to GeoJSON

### data

* [natural earth](http://www.naturalearthdata.com/): country, province, and geographical data
* [world-atlas](https://github.com/mbostock/world-atlas): customizable simplified versions of natural earth data
* [openflights-geojson](https://github.com/tmcw/openflights-geojson): [openflights](http://openflights.org/) airports & airplane routes
* [us-atlas](https://github.com/mbostock/us-atlas): geojson & topojson for United States features
* [metro-extracts](https://mapzen.com/metro-extracts/): regional OpenStreetMap data as GeoJSON
* [whereonearth-airport](https://github.com/straup/whereonearth-airport): outlines of every airport
* [whereonearth-building](https://github.com/straup/whereonearth-building/): building outlines
* [whereonearth repos](https://github.com/search?q=user%3Astraup+whereonearth): other features output from GeoPlanet by Aaron Straup Cope
* [tgn-geojson](https://github.com/straup/tgn-geojson): The Getty Thesaurus of Geographic Names (TGN) As GeoJSON.
* [strava-to-geojsonio](https://github.com/taketime/strava-to-geojsonio): export runs & rides from Strava to GeoJSON
* [strava-geojson](https://github.com/tmcw/strava-geojson): export _all_ strava data to geojson, in node & [on the web](http://www.macwright.org/strava-geojson/)

### serialization

* [python-geojson](https://github.com/frewsxcv/python-geojson): serialize geojson to/from python datatypes
* [rust-geojson](https://github.com/georust/rust-geojson): serialize geojson to/from rust datatypes

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Tom MacWright](http://macwright.org) has waived all copyright and related or neighboring rights to this work.
