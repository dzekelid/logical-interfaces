---
name: IBM Watson
x-slug: ibm-watson
description: Meet IBM Watson, a cognitive system that enables a new partnership between
  people and computers that enhances and scales human expertise. Watson has been learning
  the language of professions and is trained by experts to work across many different
  industries.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Logical Interfaces
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/apis.md
specificationVersion: "0.14"
apis:
- name: IBM Watson IoT Platform HTTP REST API - Query active logical interfaces
  x-api-slug: logicalinterfaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active logical interface
  x-api-slug: logicalinterfaceslogicalinterfaceid-get
  description: Retrieve the active logical interface with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a logical
    interface
  x-api-slug: logicalinterfaceslogicalinterfaceid-patch
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft logical interfaces
  x-api-slug: draftlogicalinterfaces-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft logical interface
  x-api-slug: draftlogicalinterfaces-post
  description: |-
    Creates a new draft logical interface for the organization in the
    Watson IoT Platform. The logical interface must reference a schema
    definition that defines the structure of the state that will be stored
    for the device or thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaces-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-get
  description: Retrieve the draft logical interface with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-put
  description: "Updates the draft logical interface with the specified id. The\nfollowing
    properties can be updated: \n\n  - name\n  - description\n  - schemaId\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the logical\ninterface.\n  \nAny changes
    made to the values of the following properties will be\nignored:\n\n  - created\n
    \ - createdBy\n  - updated\n  - updatedBy\n  - refs\n  \nThe values of these properties
    are set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a draft
    logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-patch
  description: "Performs the specified operation against the draft logical\ninterface.
    The following values can be specified for the operation\nproperty:\n\n  - validate-configuration\n
    \ - activate-configuration\n  - list-differences\n\nThe **validate-configuration**
    operation will analyze all of the \nconfiguration associated with the draft logical
    interface to\ndetermine if it is valid.  If the configuration is invalid, a list
    of \nthe issues will be returned in the body of the response.  \n \nThe **activate-configuration**
    operation will make the configuration\nassociated with the draft logical interface
    active. The \n**activate-configuration** operation must have been performed against\na
    draft logical interface before any state is generated for device\nor thing types
    that are associated with that logical interface.\n\nThe **list-differences** operation
    will return a list of the differences\nthat exist between the active configuration
    for the logical\ninterface, if any, and the draft configuration."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Deletes the draft logical interface with the specified id from the
    organization in the Watson IoT Platform.

    Please note the the delete will fail if the draft logical interface
    is being referenced by a device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query active rules
  x-api-slug: logicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/logicalinterfaces/{logicalInterfaceId}/rules** endpoint returns
    the list of all of the active rules that have been associated with the
    logical interface. Various query parameters can be used to filter, sort
    and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active rule
  x-api-slug: logicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the active rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft rules
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/draft/logicalinterfaces/{logicalInterfaceId}/rules** endpoint
    returns the list of all of the draft rules that have been associated
    with the logical interface. Various query parameters can be used to
    filter, sort and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-post
  description: |-
    Creates a new draft rule that is associated with the logical interface
    for the organization in the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the draft rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-put
  description: "Updates the draft rule with the specified id. The following properties\ncan
    be updated: \n\n  - name\n  - description\n  - condition\n\nNote that if the description
    field is omitted from the body of the\nupdate, then any existing description will
    be removed from the rule.\n  \nAny changes made to the values of the following
    properties will be\nignored:\n\n  - created\n  - createdBy\n  - updated\n  - updatedBy\n
    \ - refs\n  \nThe values of these properties are set on the server as a result
    of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete
  description: |-
    Deletes the draft rule with the specified id from the organization in
    the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of active logical interfaces associated with the device
    type
  x-api-slug: devicetypestypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of active logical interfaces that have been
    associated with the device type.  At least one logical interface
    must be associated with the device type before any mappings can be
    defined that will generate state for the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeidlogicalinterfaces-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of draft logical interfaces associated with the device
    type
  x-api-slug: draftdevicetypestypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of draft logical interfaces that have been
    associated with the device type.  At least one active logical
    interface must be associated with the device type before any mappings
    can be defined that will generate state for the device.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Associate a draft logical interface
    with the device type
  x-api-slug: draftdevicetypestypeidlogicalinterfaces-post
  description: |-
    Associates a draft logical interface with the specified device type.
    The draft logical interface must already exist within the organization
    in the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidlogicalinterfaces-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a draft logical interface
    from the device type
  x-api-slug: draftdevicetypestypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface  with the specified id
    from the device type.

    Please note the the delete will fail if the draft logical interface
    being removed from the device type is referenced in the property
    mappings for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of active logical interfaces associated with the thing
    type
  x-api-slug: thingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of active logical  interfaces that have been associated
    with the thing type.  At least one logical interface must be associated
    with the thing type before any mappings can be defined that will generate
    state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/thingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the list of draft logical interfaces associated with the thing
    type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-get
  description: |-
    Retrieve the list of draft logical interfaces that have been associated
    with the draft thing type.  At least one logical interface must be
    associated with the thing type before any mappings can be defined that
    will generate state for the thing.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Associate a draft logical interface
    with the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaces-post
  description: |-
    Associates a draft logical interface with the specified draft thing type.
    The logical interface must already exist within the organization in the
    Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaces-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a logical interface from
    the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface with the specified id from the
    draft thing type.

    Please note the the delete will fail if the logical interface being
    removed from the draft thing type is referenced in the property mappings
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active logical interface
  x-api-slug: logicalinterfaceslogicalinterfaceid-get
  description: Retrieve the active logical interface with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a logical
    interface
  x-api-slug: logicalinterfaceslogicalinterfaceid-patch
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-get
  description: Retrieve the draft logical interface with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-put
  description: "Updates the draft logical interface with the specified id. The\nfollowing
    properties can be updated: \n\n  - name\n  - description\n  - schemaId\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the logical\ninterface.\n  \nAny changes
    made to the values of the following properties will be\nignored:\n\n  - created\n
    \ - createdBy\n  - updated\n  - updatedBy\n  - refs\n  \nThe values of these properties
    are set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a draft
    logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-patch
  description: "Performs the specified operation against the draft logical\ninterface.
    The following values can be specified for the operation\nproperty:\n\n  - validate-configuration\n
    \ - activate-configuration\n  - list-differences\n\nThe **validate-configuration**
    operation will analyze all of the \nconfiguration associated with the draft logical
    interface to\ndetermine if it is valid.  If the configuration is invalid, a list
    of \nthe issues will be returned in the body of the response.  \n \nThe **activate-configuration**
    operation will make the configuration\nassociated with the draft logical interface
    active. The \n**activate-configuration** operation must have been performed against\na
    draft logical interface before any state is generated for device\nor thing types
    that are associated with that logical interface.\n\nThe **list-differences** operation
    will return a list of the differences\nthat exist between the active configuration
    for the logical\ninterface, if any, and the draft configuration."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Deletes the draft logical interface with the specified id from the
    organization in the Watson IoT Platform.

    Please note the the delete will fail if the draft logical interface
    is being referenced by a device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query active rules
  x-api-slug: logicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/logicalinterfaces/{logicalInterfaceId}/rules** endpoint returns
    the list of all of the active rules that have been associated with the
    logical interface. Various query parameters can be used to filter, sort
    and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active rule
  x-api-slug: logicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the active rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft rules
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/draft/logicalinterfaces/{logicalInterfaceId}/rules** endpoint
    returns the list of all of the draft rules that have been associated
    with the logical interface. Various query parameters can be used to
    filter, sort and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-post
  description: |-
    Creates a new draft rule that is associated with the logical interface
    for the organization in the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the draft rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-put
  description: "Updates the draft rule with the specified id. The following properties\ncan
    be updated: \n\n  - name\n  - description\n  - condition\n\nNote that if the description
    field is omitted from the body of the\nupdate, then any existing description will
    be removed from the rule.\n  \nAny changes made to the values of the following
    properties will be\nignored:\n\n  - created\n  - createdBy\n  - updated\n  - updatedBy\n
    \ - refs\n  \nThe values of these properties are set on the server as a result
    of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete
  description: |-
    Deletes the draft rule with the specified id from the organization in
    the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface
    for a device type.
  x-api-slug: devicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a draft logical interface
    from the device type
  x-api-slug: draftdevicetypestypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface  with the specified id
    from the device type.

    Please note the the delete will fail if the draft logical interface
    being removed from the device type is referenced in the property
    mappings for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the device with
    the specified id
  x-api-slug: devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-get
  description: Retrieve the current state of the device with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the device
    state for a logical interface
  x-api-slug: devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the device state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    device to the default values as defined by the schema for the logical
    interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-patch-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface for
    a thing type.
  x-api-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/thingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a logical interface from
    the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface with the specified id from the
    draft thing type.

    Please note the the delete will fail if the logical interface being
    removed from the draft thing type is referenced in the property mappings
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the property mappings for a specific logical interface for
    the thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the property mappings for a specific logical interface for
    the draft thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the thing
    state for a logical interface
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the thing state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    thing instance to the default values as defined by the schema for the
    logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the thing with the
    specified id
  x-api-slug: thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get
  description: Retrieve the current state of the thing with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/thingtypesthingtypeidthingsthingidstatelogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the property mappings for a specific logical interface for
    the draft thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the property mappings for a specific logical interface for
    the thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the property mappings for a specific logical interface
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a thing type.
  x-api-slug: draftthingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a logical interface from
    the draft thing type
  x-api-slug: draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface with the specified id from the
    draft thing type.

    Please note the the delete will fail if the logical interface being
    removed from the draft thing type is referenced in the property mappings
    for the draft thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftthingtypesthingtypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface for
    a thing type.
  x-api-slug: thingtypesthingtypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical interface
    for the thing type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/thingtypesthingtypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against the device
    state for a logical interface
  x-api-slug: devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-patch
  description: |-
    Performs the specified operation against the device state for a logical
    interface. The following values can be specified for the operation
    property:

      - reset-state

    The **reset-state** operation will reset the state of the specified
    device to the default values as defined by the schema for the logical
    interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get the state for the device with
    the specified id
  x-api-slug: devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-get
  description: Retrieve the current state of the device with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeiddevicesdeviceidstatelogicalinterfaceid-get-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Delete the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-delete
  description: |-
    Deletes the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Update the draft property mappings for a specific logical interface
    for the device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-put
  description: |-
    Updates the draft property mappings for a specific logical interface
    for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-put-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the draft property mappings for a specific logical interface for
    a device type.
  x-api-slug: draftdevicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the draft property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Disassociate a draft logical interface
    from the device type
  x-api-slug: draftdevicetypestypeidlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Disassociates the draft logical interface  with the specified id
    from the device type.

    Please note the the delete will fail if the draft logical interface
    being removed from the device type is referenced in the property
    mappings for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftdevicetypestypeidlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: |-
    IBM Watson IoT Platform HTTP REST API - Get the active property mappings for a specific logical interface
    for a device type.
  x-api-slug: devicetypestypeidmappingslogicalinterfaceid-get
  description: |-
    Retrieves the active property mappings for a specific logical
    interface for the device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/devicetypestypeidmappingslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete
  description: |-
    Deletes the draft rule with the specified id from the organization in
    the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-put
  description: "Updates the draft rule with the specified id. The following properties\ncan
    be updated: \n\n  - name\n  - description\n  - condition\n\nNote that if the description
    field is omitted from the body of the\nupdate, then any existing description will
    be removed from the rule.\n  \nAny changes made to the values of the following
    properties will be\nignored:\n\n  - created\n  - createdBy\n  - updated\n  - updatedBy\n
    \ - refs\n  \nThe values of these properties are set on the server as a result
    of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the draft rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Create a draft rule
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-post
  description: |-
    Creates a new draft rule that is associated with the logical interface
    for the organization in the Watson IoT Platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-post-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query draft rules
  x-api-slug: draftlogicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/draft/logicalinterfaces/{logicalInterfaceId}/rules** endpoint
    returns the list of all of the draft rules that have been associated
    with the logical interface. Various query parameters can be used to
    filter, sort and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active rule
  x-api-slug: logicalinterfaceslogicalinterfaceidrulesruleid-get
  description: |-
    Retrieve the active rule with the specified id that has been associated
    with the specified logical interface.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrulesruleid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Query active rules
  x-api-slug: logicalinterfaceslogicalinterfaceidrules-get
  description: |-
    Rules allow you to specify conditions that can be used to trigger
    actions. For example, you might create a rule that sends an email if
    the temperature of a device exceeds a certain value.

    Rules are defined against a specific logical interface schema.  At
    runtime, a rule will be evaluated whenever the state for a Device that
    exposes the logical interface changes.

    The **/logicalinterfaces/{logicalInterfaceId}/rules** endpoint returns
    the list of all of the active rules that have been associated with the
    logical interface. Various query parameters can be used to filter, sort
    and page through the list of rules that are returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceidrules-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Delete a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-delete
  description: |-
    Deletes the draft logical interface with the specified id from the
    organization in the Watson IoT Platform.

    Please note the the delete will fail if the draft logical interface
    is being referenced by a device type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-delete-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a draft
    logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-patch
  description: "Performs the specified operation against the draft logical\ninterface.
    The following values can be specified for the operation\nproperty:\n\n  - validate-configuration\n
    \ - activate-configuration\n  - list-differences\n\nThe **validate-configuration**
    operation will analyze all of the \nconfiguration associated with the draft logical
    interface to\ndetermine if it is valid.  If the configuration is invalid, a list
    of \nthe issues will be returned in the body of the response.  \n \nThe **activate-configuration**
    operation will make the configuration\nassociated with the draft logical interface
    active. The \n**activate-configuration** operation must have been performed against\na
    draft logical interface before any state is generated for device\nor thing types
    that are associated with that logical interface.\n\nThe **list-differences** operation
    will return a list of the differences\nthat exist between the active configuration
    for the logical\ninterface, if any, and the draft configuration."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Update a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-put
  description: "Updates the draft logical interface with the specified id. The\nfollowing
    properties can be updated: \n\n  - name\n  - description\n  - schemaId\n\nNote
    that if the description field is omitted from the body of the\nupdate, then any
    existing description will be removed from the logical\ninterface.\n  \nAny changes
    made to the values of the following properties will be\nignored:\n\n  - created\n
    \ - createdBy\n  - updated\n  - updatedBy\n  - refs\n  \nThe values of these properties
    are set on the server as a result of a\nsuccessful update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-put-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get a draft logical interface
  x-api-slug: draftlogicalinterfaceslogicalinterfaceid-get
  description: Retrieve the draft logical interface with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/draftlogicalinterfaceslogicalinterfaceid-get-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Perform an operation against a logical
    interface
  x-api-slug: logicalinterfaceslogicalinterfaceid-patch
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceid-patch-openapi.md
- name: IBM Watson IoT Platform HTTP REST API - Get an active logical interface
  x-api-slug: logicalinterfaceslogicalinterfaceid-get
  description: Retrieve the active logical interface with the specified id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ibm-watson-logo.png
  humanURL: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
  baseURL: https:////api/v0002
  tags: Machine Learning, Machine Learning, AI, API LIfeyclessss, Stack Network, Stack,
    Getting Started Example, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logical-interfaces/master/_listings/ibm-watson/logicalinterfaceslogicalinterfaceid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://ibm.financial.crimes.insight.for.insurance.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ibm.watson.stack.network
- type: x-application-gallery
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/gallery.html
- type: x-blog
  url: https://developer.ibm.com/watson/blog/
- type: x-blog-rss
  url: https://developer.ibm.com/watson/feed/
- type: x-developer
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/
- type: x-developer
  url: https://developer.ibm.com/watson/
- type: x-documentation
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/apis/
- type: x-forum
  url: https://developer.ibm.com/answers/smartspace/watson/
- type: x-getting-started
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/getstarted.html
- type: x-github
  url: https://github.com/IBM-Watson
- type: x-partners
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/ecosystem.html
- type: x-privacy
  url: http://www.ibm.com/privacy/us/en/?lnk=flg-priv-usen
- type: x-terms-of-service
  url: http://www.ibm.com/legal/us/en/?lnk=flg-tous-usen
- type: x-twitter
  url: https://twitter.com/IBMWatson
- type: x-videos
  url: http://www.ibm.com/smarterplanet/us/en/ibmwatson/
- type: x-website
  url: https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/
- type: x-white-papers
  url: https://developer.ibm.com/watson/docs/whitepapers/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---