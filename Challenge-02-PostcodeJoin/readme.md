# Challenge 02: Join Addresses to Postcodes

## Scenario
Join a CSV of UK address points to a shapefile of postcode polygons using spatial logic.

## Workflow Summary
- **CSV Reader**: Loads address data
- **Shapefile Reader**: Loads postcode boundaries
- **CoordinateSystemSetter**: Aligns spatial reference
- **GeometryCreator**: Converts lat/lon to points
- **SpatialJoiner**: Matches each point to its postcode polygon
- **GeoJSON Writer**: Outputs joined data

## Outcome
A GeoJSON file with addresses tagged by postcode, ready for mapping or analysis.

## Notes
This simulates a common GIS analyst workflow: spatial joins between tabular and polygon data.
