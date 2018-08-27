---
swagger: "2.0"
x-collection-name: Transavia
x-complete: 0
info:
  title: Transavia Routes API Get all routes by origin and/or destination
  description: Retrieves all routes.
  version: 1.0.0
host: tst.api.transavia.com
basePath: /v3/routes
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:
    get:
      summary: Get all routes by origin and/or destination
      description: Retrieves all routes.
      operationId: 58d3ca3eab95b50fe4da10fd
      x-api-path-slug: get
      parameters:
      - in: query
        name: Destination
        description: IATA-code (3 characters) of the destination airport
      - in: query
        name: Origin
        description: IATA-code (3 characters) of the origin airport
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Airplanes
      - Routes
  /countrycode/{countryCode}:
    get:
      summary: Get Country Codes
      description: Retrieve airports by country code.
      operationId: countrycode.countryCode.get
      x-api-path-slug: countrycodecountrycode-get
      parameters:
      - in: path
        name: countryCode
        description: Comma-separated list of country codes (2-character ISO 3166-1)
      responses:
        200:
          description: OK
      tags:
      - Airports
      - Countrycode
  /nearest:
    get:
      summary: Get Nearest Airports
      description: Retrieve nearest airports by geo coordinates (latitude/longitude).
      operationId: nearest.get
      x-api-path-slug: nearest-get
      parameters:
      - in: query
        name: latitude
        description: Latitude in decimals, lower than -90
      - in: query
        name: limit
        description: Limits the result, lower than 0 is not allowed
      - in: query
        name: longitude
        description: Longitude in decimals, lower than -180
      - in: query
        name: maxDistanceInKm
        description: Maximum distance in kilometers, lower than 1 and higher than
          500 is not allowed
      responses:
        200:
          description: OK
      tags:
      - Airports
      - Nearest
  /nearest/{id}:
    get:
      summary: Get Nearest Airport
      description: Retrieve nearest airports by station id.
      operationId: nearest.id.get
      x-api-path-slug: nearestid-get
      parameters:
      - in: path
        name: id
        description: Airport (IATA code) to search nearest airports for
      - in: query
        name: limit
        description: Limits the result, lower than 0 is not allowed
      - in: query
        name: maxDistanceInKm
        description: Maximum distance in kilometers, lower than 1 and higher than
          500 is not allowed
      responses:
        200:
          description: OK
      tags:
      - Airports
      - Nearest
  /{id}:
    get:
      summary: Get Aiport
      description: Retrieve airport by id.
      operationId: id.get
      x-api-path-slug: id-get
      parameters:
      - in: path
        name: id
        description: Airport code (3-character IATA code)
      responses:
        200:
          description: OK
      tags:
      - Airports
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---