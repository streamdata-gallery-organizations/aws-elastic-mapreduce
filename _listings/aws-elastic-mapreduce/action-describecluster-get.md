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
  /?Action=DescribeCluster:
    get:
      summary: ' Describe Cluster '
      description: Provides cluster-level details including status, hardware and software
        configuration, VPC settings, and so on
      operationId: describeCluster
      parameters:
      - in: query
        name: ClusterId
        description: The identifier of the cluster to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - clusters
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