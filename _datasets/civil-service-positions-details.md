---
category:
- Budget / Finance
- Economy
extras: {}
license: Other (City of Philadelphia)
maintainer: Jerome Lomax
maintainer_email: jerome.lomax@phila.gov
notes: "These datasets show job classification and pay ranges details about Civil\
  \ Service positions approved by the Civil Service commission and Administrative\
  \ board.\r\n\r\nTrouble downloading or have questions about this City dataset? Visit\
  \ the [OpenDataPhilly Discussion Group](http://www.phila.gov/data/discuss/)"
organization: City of Philadelphia
resources:
- description: ''
  format: CSV
  name: Job Classifications (CSV)
  url: https://phl.carto.com/api/v2/sql?filename=job_class&format=csv&skipfields=cartodb_id,the_geom,the_geom_webmercator&q=SELECT
    * FROM job_class
- description: ''
  format: API
  name: Job Classifications (API)
  url: https://cityofphiladelphia.github.io/carto-api-explorer/#job_class
- description: ''
  format: HTML
  name: Job Classifications (Metadata)
  url: https://metadata.phila.gov/#home/datasetdetails/62fe7bbd4fc5860021be5c87/representationdetails/62fe7d383bf07a0021232f6b/
- description: ''
  format: CSV
  name: Pay Ranges (CSV)
  url: https://phl.carto.com/api/v2/sql?filename=pay_range&format=csv&skipfields=cartodb_id,the_geom,the_geom_webmercator&q=SELECT
    * FROM pay_range
- description: ''
  format: API
  name: Pay Ranges (API)
  url: https://cityofphiladelphia.github.io/carto-api-explorer/#pay_range
- description: ''
  format: HTML
  name: Pay Ranges (Metadata)
  url: https://metadata.phila.gov/#home/datasetdetails/62fe7bbd4fc5860021be5c87/representationdetails/630651053330120025907856/
schema: default
tags: []
title: Civil Service Positions Details
---