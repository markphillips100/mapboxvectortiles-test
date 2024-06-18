## Test data for rendering mapbox vector tiles of a simple polygon

1. Tiles generated from sample3.json using https://github.com/NetTopologySuite/NetTopologySuite.IO.VectorTiles/tree/fix/issue29.
2. All tiles render fine in qgis.
3. Test zoom level 19 and 20 have the greatest rendering issue.  Tiles `485000,303779,19` and `485001,303779,19` are the 2 to focus on for zoom level 19.
