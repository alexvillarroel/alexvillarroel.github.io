---
layout: post
title: a post with geojson
date: 2024-01-26 17:57:00
description: this is what included geojson code could look like
tags: formatting charts maps
categories: sample-posts
map: true
---

This is an example post with some [geojson](https://geojson.org/) code making a polygon of University of Concepción. The support is provided thanks to [Leaflet](https://leafletjs.com/). To create your own visualization, go to [geojson.io](https://geojson.io/).

````markdown
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              -73.03972349903334,
              -36.82728520895258
            ],
            [
              -73.03674772284866,
              -36.83191362736232
            ],
            [
              -73.03377194666479,
              -36.833645828908395
            ],
            [
              -73.03225024293411,
              -36.83564863804883
            ],
            [
              -73.02822618195785,
              -36.83242787878949
            ],
            [
              -73.03343379028067,
              -36.825119770866976
            ],
            [
              -73.03664627593369,
              -36.82612129359917
            ],
            [
              -73.03972349903334,
              -36.82728520895258
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```
````

Which generates:

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              -73.03972349903334,
              -36.82728520895258
            ],
            [
              -73.03674772284866,
              -36.83191362736232
            ],
            [
              -73.03377194666479,
              -36.833645828908395
            ],
            [
              -73.03225024293411,
              -36.83564863804883
            ],
            [
              -73.02822618195785,
              -36.83242787878949
            ],
            [
              -73.03343379028067,
              -36.825119770866976
            ],
            [
              -73.03664627593369,
              -36.82612129359917
            ],
            [
              -73.03972349903334,
              -36.82728520895258
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```
