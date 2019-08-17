# georectify-json-spec

Draft specification for JSON data model for map georectification.

Created during [Wikimania Hackathon 2019](https://wikimania.wikimedia.org/wiki/2019:Hackathon).

## Goal

There is need for a single way to describe georectified (historical) maps.

This data model should specify the following properties:

  - the mapping between pixels on the scanned map and geospatial coordinates,
  - the masking/clipping polygon to remove non-cartographic material,
  - the source (or multiple sources) of the map image,
  - the transformation type

## JSON Schema

This repository holds a JSON Schema to verify and describe JSON data with map georectification data.

## See also

- https://observablehq.com/@bertspaan/proposal-for-wikimania-2019-hackathon
- https://phabricator.wikimedia.org/T227036
- https://github.com/bertspaan/wikimania-hackathon-2019
- https://github.com/bertspaan/georectify-service
