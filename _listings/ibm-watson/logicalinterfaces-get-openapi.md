---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson IoT Platform Query active logical interfaces
  description: |-
    Logical interfaces are used to model the interfaces exposed by a
    device or thing in the Watson IoT Platform. A logical interface
    must reference a schema definition that defines the structure of the
    state that will be stored for the device or thing.

    The **logicalinterfaces** endpoint returns the list of all of the
    active logical interfaces that have been defined for the organization
    in the Watson IoT Platform.  Various query parameters can
    be used to filter, sort and page through the list of active logical
    interfaces that are returned.
  version: 1.0.0
basePath: /api/v0002
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /logicalinterfaces:
    get:
      summary: Query active logical interfaces
      description: |-
        Logical interfaces are used to model the interfaces exposed by a
        device or thing in the Watson IoT Platform. A logical interface
        must reference a schema definition that defines the structure of the
        state that will be stored for the device or thing.

        The **logicalinterfaces** endpoint returns the list of all of the
        active logical interfaces that have been defined for the organization
        in the Watson IoT Platform.  Various query parameters can
        be used to filter, sort and page through the list of active logical
        interfaces that are returned.
      operationId: logical-interfaces-are-used-to-model-the-interfaces-exposed-by-adevice-or-thing-in-the-watson-iot-pl
      x-api-path-slug: logicalinterfaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Logical interfaces
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