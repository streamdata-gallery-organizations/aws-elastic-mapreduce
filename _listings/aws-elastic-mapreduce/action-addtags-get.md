---
swagger: "2.0"
info:
  title: AWS Elastic MapReduce API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AddTags:
    get:
      summary: ' Add Tags '
      description: Adds tags to an Amazon EMR resource
      operationId: addTags
      parameters:
      - in: query
        name: ResourceId
        description: The Amazon EMR resource identifier to which tags will be added
        type: string
      - in: query
        name: Tags
        description: A list of tags to associate with a cluster and propagate to EC2
          instances
        type: string
      responses:
        200:
          description: OK
      tags:
      - tags
definitions: []
x-collection-name: AWS Elastic MapReduce
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