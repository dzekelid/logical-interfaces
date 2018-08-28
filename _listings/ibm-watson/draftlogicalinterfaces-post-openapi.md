---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson IoT Platform Create a draft logical interface
  description: |-
    Creates a new draft logical interface for the organization in the
    Watson IoT Platform. The logical interface must reference a schema
    definition that defines the structure of the state that will be stored
    for the device or thing.
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
  /logicalinterfaces/{logicalInterfaceId}:
    get:
      summary: Get an active logical interface
      description: Retrieve the active logical interface with the specified id.
      operationId: retrieve-the-active-logical-interface-with-the-specified-id
      x-api-path-slug: logicalinterfaceslogicalinterfaceid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Logical interfaces
      - LogicalInterfaceId
    patch:
      summary: Perform an operation against a logical interface
      description: |-
        Performs the specified operation against the logical interface. The
        following values can be specified for the operation property:

          - deactivate-configuration

        The **deactivate-configuration** operation will remove any active
        configuration that is currently associated with the logical
        interface. If the logical interface is associated with any device
        types, the state for any instances of those device types will be deleted
        as a result of performing the **deactivate-configuration** operation.
        The **deactivate-configuration** operation will fail if the logical
        interface is referenced by a thing schema.
      operationId: performs-the-specified-operation-against-the-logical-interface-thefollowing-values-can-be-specified-
      x-api-path-slug: logicalinterfaceslogicalinterfaceid-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: Operation
        description: The JSON representation of an operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Logical interfaces
      - LogicalInterfaceId
  /draft/logicalinterfaces:
    get:
      summary: Query draft logical interfaces
      description: |-
        Logical interfaces are used to model the interfaces exposed by a
        device or thing in the Watson IoT Platform. A logical interface must
        reference a schema definition that defines the structure of the
        state that will be stored for the device or thing.

        The **logicalinterfaces** endpoint returns the list of all of the
        draft logical interfaces that have been defined for the organization
        in the Watson IoT Platform.  Various query parameters can be used to
        filter, sort and page through the list of draft logical interfaces
        that are returned.
      operationId: logical-interfaces-are-used-to-model-the-interfaces-exposed-by-adevice-or-thing-in-the-watson-iot-pl
      x-api-path-slug: draftlogicalinterfaces-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
      - Logical interfaces
    post:
      summary: Create a draft logical interface
      description: |-
        Creates a new draft logical interface for the organization in the
        Watson IoT Platform. The logical interface must reference a schema
        definition that defines the structure of the state that will be stored
        for the device or thing.
      operationId: creates-a-new-draft-logical-interface-for-the-organization-in-thewatson-iot-platform-the-logical-int
      x-api-path-slug: draftlogicalinterfaces-post
      parameters:
      - in: body
        name: Logical Interface
        description: The JSON representation of the draft logical interface
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Internet of Things
      - Draft
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