# Robert C. Corby Arboretum Boundary

This contains the legal description of the Robert C. Corby Arboretum and Wildlife Sanctuary and work to render it on a map. This park is on a parcel of land owned by the Village of Pittsford (tax parcel 151.18-1-1.1).

On June 13, 2023 the Village of Pittsford Board of Trustees adopted a resolution to permanently dedicate the area described by the metes and bounds description as parkland.

## Map Projection

This project should be rendered using EPSG:2262 NAD83 / New York West (ftUS).

## Files

* Legal descriptions

	* DPW ARBORETUM AREA 1 R2.pdf - main area of parkland NW of Village Lane measuring 9.17 acres.
	* DPW ARBORETUM AREA 2.pdf - legal description of parkland area 2 SE of Village Lane, measuring 0.28 acres.

* Azimuth / distance descriptions (for import into QGIS Azimuth/Distance plugin)
	* Parkland Area 1 Azimuth Distance.txt
	* Parkland Area 2 Azimuth Distance.txt

Maps in shapefile, PDF and PNG under maps/.

Shapefiles are divided into folders:

* "Lines from metes and bounds" contains the shape files following the legal description. This rotates around the described feature forming a line.
* "Polygons based on metes and bounds" are polygons that were created based on the above lines found in the metes and bounds. These are the areas that are dedicated as parkland.

* "DRAFT resolution to dedicate parkland in the Northwest Quadrant v3.pdf" is the resolution adopted by the Board on June 13, 2023.
