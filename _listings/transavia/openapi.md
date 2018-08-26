---
swagger: "2.0"
x-collection-name: Transavia
x-complete: 1
info:
  title: Routes API v3
  description: returns-all-available-routes
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
  /{id}:
    get:
      summary: Get route by id
      description: Gets the route. Note, this request doesn't have a data property
        in the response.
      operationId: 58d3ca3eab95b50fe4da10fe
      x-api-path-slug: id-get
      parameters:
      - in: path
        name: id
        description: Route identifier, {origin airport IATA-code}-{destination airport
          IATA-code}
      responses:
        2:
          description: Successful response
        200:
          description: Successful response
      tags:
      - Airplanes
      - Routes
---