# Challenge 01: Filter Reading Bus Stops

## Scenario
Given a CSV of UK bus stops, filter only those located in Reading and output to GeoJSON.
## Workflow Summary
- **CSV Reader**: Loads the bus stop data
- **Tester**: Filters rows where `Town = 'Reading'`
- **GeometryCreator**: Converts lat/lon to spatial points
- **GeoJSON Writer**: Outputs filtered data to GeoJSON
## Outcome
A clean GeoJSON file of Reading bus stops, ready for mapping or dashboard use.
## Notes
This simulates a real GIS analyst task: filtering and spatialising tabular data.
