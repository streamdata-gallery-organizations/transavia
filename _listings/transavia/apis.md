---
name: Transavia
x-slug: transavia
description: Want to fly affordably to more than 100 destinations in Europe? Book
  a flight with Transavia!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
x-kinRank: "7"
x-alexaRank: "12365"
tags: Transavia
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/apis.md
specificationVersion: "0.14"
apis:
- name: Airports API v2 - Get Airports
  x-api-slug: get
  description: Retrieve all airports.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://api.transavia.com//v2/airports
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/get-openapi.md
- name: Airports API v2 - Get Country Codes
  x-api-slug: countrycodecountrycode-get
  description: Retrieve airports by country code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://api.transavia.com//v2/airports
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/countrycodecountrycode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/countrycodecountrycode-get-openapi.md
- name: Airports API v2 - Get Nearest Airports
  x-api-slug: nearest-get
  description: Retrieve nearest airports by geo coordinates (latitude/longitude).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://api.transavia.com//v2/airports
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/nearest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/nearest-get-openapi.md
- name: Airports API v2 - Get Nearest Airport
  x-api-slug: nearestid-get
  description: Retrieve nearest airports by station id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://api.transavia.com//v2/airports
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/nearestid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/nearestid-get-openapi.md
- name: Airports API v2 - Get Aiport
  x-api-slug: id-get
  description: Retrieve airport by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://api.transavia.com//v2/airports
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/id-get-openapi.md
- name: Flight Offers API v1 - Flight offers
  x-api-slug: get
  description: Retrieve flight offers by query string parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://tst.api.transavia.com//v1/flightoffers
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/get-openapi.md
- name: Routes API v3 - Get all routes by origin and/or destination
  x-api-slug: get
  description: Retrieves all routes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://tst.api.transavia.com//v3/routes
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/get-openapi.md
- name: Routes API v3 - Get route by id
  x-api-slug: id-get
  description: Gets the route. Note, this request doesn't have a data property in
    the response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://tst.api.transavia.com//v3/routes
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/transavia/master/_listings/transavia/id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://tradestation.api.gallery.streamdata.io
- type: x-api-stack
  url: http://transavia.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/transavia-airlines
- type: x-developer
  url: https://developer.transavia.com/
- type: x-documentation
  url: https://tst.developer.transavia.com/docs/services/
- type: x-twitter
  url: https://twitter.com/transavia
- type: x-website
  url: http://transavia.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---