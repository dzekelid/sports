---
swagger: "2.0"
x-collection-name: AWS EC2
x-complete: 0
info:
  title: AWS EC2 API Describe Spot Fleet Requests
  version: 1.0.0
  description: Describes your Spot fleet requests.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeSpotFleetRequests:
    get:
      summary: Describe Spot Fleet Requests
      description: Describes your Spot fleet requests.
      operationId: describespotfleetrequests
      x-api-path-slug: actiondescribespotfleetrequests-get
      responses:
        200:
          description: OK
      tags:
      - Sport Fleet Requests
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