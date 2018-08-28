---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Confluence Cloud API Update restrictions
  description: "Updates restrictions for a piece of content. This removes the existing
    \nrestrictions and replaces them with the restrictions in the request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  termsOfService: http://atlassian.com/terms/
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /content/{id}/restriction:
    get:
      summary: Get restrictions
      description: "Returns the restrictions on a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to view the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentRestrictionResource.getRestrictions_get
      x-api-path-slug: contentidrestriction-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          restrictions to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its restrictions
      - in: query
        name: limit
        description: The maximum number of users and the maximum number of groups,
          in the returned restrictions, to return per page
      - in: query
        name: start
        description: The starting index of the users and groups in the returned restrictions
      responses:
        200:
          description: OK
      tags:
      - Restrictions
    post:
      summary: Add restrictions
      description: "Adds restrictions to a piece of content. Note, this does not change
        any \nexisting restrictions on the content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to edit the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentRestrictionResource.addRestrictions_post
      x-api-path-slug: contentidrestriction-post
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          restrictions (returned in response) to expand
      - in: path
        name: id
        description: The ID of the content to add restrictions to
      responses:
        200:
          description: OK
      tags:
      - Restrictions
    put:
      summary: Update restrictions
      description: "Updates restrictions for a piece of content. This removes the
        existing \nrestrictions and replaces them with the restrictions in the request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to edit the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentRestrictionResource.updateRestrictions_put
      x-api-path-slug: contentidrestriction-put
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          restrictions (returned in response) to expand
      - in: path
        name: id
        description: The ID of the content to update restrictions for
      responses:
        200:
          description: OK
      tags:
      - Restrictions
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