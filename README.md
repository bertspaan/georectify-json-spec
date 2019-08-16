oplossen:

bestand moet 2 maskers!!!





OF:


image heeft pixelmasker



en dan geotiff is nieuw ding, heeft latlongmasker!!!





========================================================================
========================================================================
========================================================================


Origineel:

  - Masker in pixels
  - GCPs: pixels -> lat/lon
  - Dimensies: [w, h]
  - brontype: [IIIF, wikicommons, ...]

Warped:

  - Masker in lat/lon
  - GCPs
  - Dimensies: [w, h]
  - brontype: [iiif, commons, geotiff, TMS, ...]
  - source: link to original


image:
  prop:mask -> [pixels]
  prop GCPs -> Data:tab file

  generated:
  prop:mask -> [lat/long]
