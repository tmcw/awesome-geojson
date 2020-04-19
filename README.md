# awesome geojson [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

GeoJSON utilities that will make your life easier.

### operations

* [CoGran](https://github.com/berlinermorgenpost/cogran): Resample statistics from one set of GeoJSON polygons to another
* [geo_assigner](https://github.com/stadt-karlsruhe/geo_assigner): Copy a property to all intersecting features
* [geojson-coords](https://github.com/mapbox/geojson-coords): Extract coordinates from GeoJSON
* [geojson-extent](https://www.npmjs.com/package/geojson-extent): compute the bounding box of geojson features
* [geojson-flatten](https://github.com/tmcw/geojson-flatten): flatten multi geometries into normal geometries
* [geojson-multiply](https://github.com/haoliangyu/geojson-multiply):  merge normal geojson features into one multi geometry type feature
* [geojson-js-utils](https://github.com/maxogden/geojson-js-utils): JavaScript helper functions for manipulating GeoJSON
* [geojson-merge](https://github.com/mapbox/geojson-merge): Merge multiple GeoJSON files into one FeatureCollection.
* [geojson-normalize](https://github.com/mapbox/geojson-normalize): normalize any geojson object into a geojson featurecollection
* [geojson-pick](https://www.npmjs.com/package/geojson-pick): remove all but specified properties from features in a geojson featurecollection
* [geojson-random](https://github.com/tmcw/geojson-random): generate random geojson points, lines, and polygons
* [geojson-rewind](https://github.com/mapbox/geojson-rewind): enforce ring winding order
* [rfc7946-to-d3](https://github.com/tyrasd/rfc7946-to-d3): Converts polygon winding order between rfc7946 and [d3 compatible](https://github.com/d3/d3-geo#d3-geo) conventions.
* [geojson-summary](https://github.com/mapbox/geojson-summary): get a plain-english summary of what's in a geojson file
* [point-grouper](https://github.com/substack/point-grouper): group geojson points into containing polygons
* [geojson-join](https://github.com/tmcw/geojson-join): join geojson against json, dbf, and csv files
* [simplify-geojson](https://github.com/maxogden/simplify-geojson): apply the ramer-douglas-peucker line simplification to geojson features or feature collections in JS or on the CLI
* [turf](https://github.com/Turfjs/turf): collection of functions for spatial operations and analysis
* [winnow](https://github.com/dmfenton/winnow): run sql queries against geojson with javascript
* [geojson-id-streaming](https://github.com/andrewharvey/geojson-id-streaming): Add a unique id to each Feature
* [geojson-mesh](https://github.com/andrewharvey/geojson-mesh): extract shared borders of Polygons in a GeoJSON
* [geojson-polygon-labels](https://github.com/andrewharvey/geojson-polygon-labels): generate point labels from GeoJSON polygons
* [geojsontools](https://github.com/micolous/geojsontools): Python tools for manipulating GeoJSON files


### editors & viewers

* [geojson.io](http://geojson.io/): web-based editor, supports many filetype imports & exports, operations, sharing via GitHub
* [umap](http://umap.openstreetmap.fr/en/): web-based editor, supports sharing on-site
* [geojson.tools](http://geojson.tools/): web-based editor from HERE XYZ
* [simple geojson editor](https://google-developers.appspot.com/maps/documentation/utils/geojson/): geojson editor on a google map, by google
* [mapstarter](http://mapstarter.com/): helps generate svg, images, and code from GeoJSON
* [gjv](https://github.com/anandthakker/gjv): electron app enables viewing GeoJSON locally and hack on it with turf; works offline
* [GeoJSON editor](https://tomscholz.github.io/geojson-editor/): a modified version of Google's simple geojson editor
* [geojson2image](https://github.com/brycejohnston/geojson2image): library for generating images from GeoJSON
* [dropchop](http://dropchop.io/): browser-based GIS based on Turf.js
* [Web GIS](https://drewweth.github.io/geodebugger): tools to view, inspect, and manipulate geospatial data

### validation

* [geojsonhint](https://github.com/mapbox/geojsonhint): find errors in your geojson files
* [geojson-validation](https://www.npmjs.com/package/geojson-validation): many validation functions, plus simple gjv command line tool

### services

* [geojsonio-cli](https://github.com/mapbox/geojsonio-cli): send geojson features to geojson.io from your command line
* [geojsonio-extension](https://github.com/mapbox/geojsonio-extension): chrome extension for editing github files in geojson.io
* [geojsonlint](http://geojsonlint.com/): REST interface for GeoJSON validation
* [mapshaper](http://mapshaper.org/): Simple interface for simplification and conversion of GeoJSON and TopoJSON
* [koop](https://koopjs.github.io): Server with plugins that recast Esri, GitHub, Socrata and other services as GeoJSON endpoints
* [featureserver](https://github.com/featureserver/featureserver): An open source Esri-Style Feature Server

### conversion

* **CSV**
  * [csv2geojson](https://github.com/mapbox/csv2geojson): convert CSV to geojson
  * [geojson2dsv](https://github.com/tmcw/geojson2dsv): convert geojson to CSV and TSV
* [geojson-mapnikify](https://github.com/mapbox/geojson-mapnikify): Transform GeoJSON objects into Mapnik XML stylesheets with embedded GeoJSON data and simplestyle-spec-derived styles.
* [geojson-vt](https://github.com/mapbox/geojson-vt): Slice GeoJSON into vector tiles on the fly in the browser
* [vt-geojson](https://github.com/developmentseed/vt-geojson): Extract GeoJSON from Mapbox vector tiles
* [geojson2rtree](https://github.com/maxogden/geojson2rtree): generate a static rtree (using terraformer) from a set of geojson features
* [ogr2ogr](http://www.gdal.org/ogr2ogr.html): convert anything to anything
  * [fiona](https://github.com/toblerity/fiona): nice python interface on top of ogr
* [shp2json](https://github.com/substack/shp2json): convert shapefile zip archives to streaming GeoJSON
* [togeojson](https://github.com/tmcw/togeojson): convert GPX & KML to geojson
* [tokml](https://github.com/mapbox/tokml): convert GeoJSON to KML
* [topojson](https://github.com/topojson/topojson): convert GeoJSON to & from TopoJSON, join data from CSV
* [wellknown](https://github.com/mapbox/wellknown): convert WKT to GeoJSON
* [esri2open](https://github.com/project-open-data/esri2open) converts proprietary Esri formats to GeoJSON
* [gtfs2geojson](https://github.com/tmcw/gtfs2geojson): convert GTFS transit data to GeoJSON
* [geoxform](https://github.com/koopjs/geoxform): convert any size stream of geojson into a streaming CSV, Shapefile or KML, etc.
* [supercluster](https://github.com/mapbox/supercluster): A fast GeoJSON clustering library for browsers and Node.
* **SVG**
  * [geojson-svgify](https://github.com/juliuste/geojson-svgify): Convert GeoJSON geometry paths to SVG polyline elements.
  * [geojson-to-svg-cli](https://github.com/derhuerst/geojson-to-svg-cli): Command line tool to convert GeoJSON to SVG.
  * [svg-to-geojson](https://github.com/mapbox/svg-to-geojson): Drag and drop SVG on the map and it returns GeoJSON back to you.
* [geojson2ndjson](https://www.npmjs.com/package/geojson2ndjson): convert GeoJSON to/from newline-delimited GeoJSON
* [geobuf](https://www.npmjs.com/package/geobuf/v/0.2.1): convert GeoJSON to/from GeoBuf

* **OpenStreetMap**
  * [osmtogeojson](https://github.com/tyrasd/osmtogeojson): convert OpenStreetMap data to GeoJSON
  * [osm2geojson](https://github.com/rclark/osm2geojson): converts OSM XML to GeoJSON
  * [osm2geojson](https://github.com/aspectumapp/osm2geojson): (Python) converts OSM XML and Overpass XML/JSON to GeoJSON
  * [minjur](https://github.com/mapbox/minjur): converts OpenStreetMap data to GeoJSON faster than anything else
  * [geojsontoosm](https://github.com/tyrasd/geojsontoosm): convert GeoJSON to OSM XML
  * [geojson2osm](https://github.com/Rub21/geojson2osm): convert GeoJSON to OSM XML
  * [osm-and-geojson](https://github.com/aaronlidman/osm-and-geojson): convert GeoJSON to OSM XML and OSM XML to GeoJSON
  * [geojson2osm-es6](https://github.com/DenisCarriere/geojson2osm-es6/): convert GeoJSON to OSM XML


### data

* [natural earth](http://www.naturalearthdata.com/): country, province, and geographical data
* [geojson.xyz](http://geojson.xyz/): natural earth data in web-friendly sizes with hotlinking
* [world-atlas](https://github.com/topojson/world-atlas): customizable simplified versions of natural earth data
* [geo-maps](https://github.com/simonepri/geo-maps): High Quality GeoJSON maps programmatically generated.
* [openflights-geojson](https://github.com/tmcw/openflights-geojson): [openflights](http://openflights.org/) airports & airplane routes
* [us-atlas](https://github.com/topojson/us-atlas): geojson & topojson for United States features
* [metro-extracts](https://mapzen.com/data/metro-extracts/): regional OpenStreetMap data as GeoJSON
* [whereonearth-airport](https://github.com/straup/whereonearth-airport): outlines of every airport
* [whereonearth-building](https://github.com/straup/whereonearth-building/): building outlines
* [whereonearth repos](https://github.com/search?q=user%3Astraup+whereonearth): other features output from GeoPlanet by Aaron Straup Cope
* [tgn-geojson](https://github.com/straup/tgn-geojson): The Getty Thesaurus of Geographic Names (TGN) As GeoJSON.
* [strava-to-geojsonio](https://github.com/taketime/strava-to-geojsonio): export runs & rides from Strava to GeoJSON
* [strava-geojson](https://github.com/tmcw/strava-geojson): export _all_ strava data to geojson, in node & [on the web](http://www.macwright.org/strava-geojson/)
* [gimme OSM](http://ustroetz.github.io/gimmeOSM/): Fetch geojson file by openstreetmap id
* [country-levels](https://github.com/hyperknot/country-levels-export) Full planet GeoJSON extracts, based on ISO and FIPS codes.

### serialization

* [python-geojson](https://github.com/frewsxcv/python-geojson): serialize geojson to/from python datatypes
* [rgeo-geojson](https://github.com/rgeo/rgeo-geojson): serialize geojson to/from ruby RGeo datatypes
* [rust-geojson](https://github.com/georust/rust-geojson): serialize geojson to/from rust datatypes
* [geojson-jackson](https://github.com/opendatalab-de/geojson-jackson): serialize GeoJSON to and from Java datatypes (based on [Jackson](http://wiki.fasterxml.com/JacksonHome))
* [mapbox-java](https://github.com/mapbox/mapbox-java): serialize GeoJSON to and from Java datatypes (based on [Gson](https://github.com/google/gson))

### resources

* [RFC 7946 – The GeoJSON Format](https://tools.ietf.org/html/rfc7946): the current GeoJSON standard by IETF
* [geojson.win](http://geojson.win): More readable version of the spec.
* [GeoJSON.org](http://geojson.org/): the first specification, defining all the rules for GeoJSON structures
* [More than you ever wanted to know about GeoJSON](http://www.macwright.org/2015/03/23/geojson-second-bite.html): a review of the concepts behind the specification in a more narrative format.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/ )

To the extent possible under law, [Tom MacWright](http://www.macwright.org) has waived all copyright and related or neighboring rights to this work.
