swagger: "2.0"
x-collection-name: ATTOM
x-complete: 1
info:
  title: Attom Data Solutions API
  description: attom-empowers-customers-with-better-property-data--we-warehouse-property-data-nationwide-with-myriad-data-points-on-each-parcel-including-ownership-information-latlong-square-footage-loan-types-sales-history-sales-comps-crime-schools-and-more-
  version: 1.0.0
host: search.onboard-apis.com
basePath: /communityapi/v2.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assessment/snapshot:
    get:
      summary: Returns assessment details for properties within a radius.
      description: Get snapshots of the properties within a radius of a property that
        have a total market value within a specified range.
      operationId: getAssessmentSnapshotTotal
      x-api-path-slug: assessmentsnapshot-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: query
        name: address1
        description: The first line of the mailing address
      - in: query
        name: address2
        description: The second line of the mailing address
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: maxmktttlvalue
        description: The estimated total market value from the local taxing authority
      - in: query
        name: minmktttlvalue
        description: The estimated total market value from the local taxing authority
      - in: query
        name: radius
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Assessment
      - Detailsproperties
      - Within
      - Radius
  /assessment/detail:
    get:
      summary: Returns assessment details for properties within a zip code.
      description: Get assessment details for properties within a zip code. Use propertytpe
        to select a specific property type for your search.
      operationId: assessmenDetailPropertyId
      x-api-path-slug: assessmentdetail-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: postalcode
        description: The postal code or zip code
      - in: query
        name: propertytype
        description: A specific property classification such as Detached Single Family
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Assessment
      - Detailsproperties
      - Within
      - Zip
      - Code
  /assessmenthistory/detail:
    get:
      summary: Returns assessment history and property details.
      description: Get a full detail of property characteristics and assessment history
        information for a specific property.
      operationId: assessmentHistoryDetailID
      x-api-path-slug: assessmenthistorydetail-get
      parameters:
      - in: header
        name: accept
        description: application/xml or application/json (default)
      - in: header
        name: apikey
        description: Application Key
      - in: query
        name: id
        description: property id
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Assessment
      - History
      - Property
      - Details