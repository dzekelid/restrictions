---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Restrictions
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: The Confluence Cloud REST API - Get restrictions
  x-api-slug: contentidrestriction-get
  description: "Returns the restrictions on a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-get-openapi.md
- name: The Confluence Cloud REST API - Add restrictions
  x-api-slug: contentidrestriction-post
  description: "Adds restrictions to a piece of content. Note, this does not change
    any \nexisting restrictions on the content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-post-openapi.md
- name: The Confluence Cloud REST API - Update restrictions
  x-api-slug: contentidrestriction-put
  description: "Updates restrictions for a piece of content. This removes the existing
    \nrestrictions and replaces them with the restrictions in the request.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-put-openapi.md
- name: The Confluence Cloud REST API - Delete restrictions
  x-api-slug: contentidrestriction-delete
  description: "Removes all restrictions (read and update) on a piece of content.\n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to edit the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestriction-delete-openapi.md
- name: The Confluence Cloud REST API - Get restrictions by operation
  x-api-slug: contentidrestrictionbyoperation-get
  description: "Returns restrictions on a piece of content by operation. This method
    is \nsimilar to [Get restrictions](#api-content-id-restriction-get) except that
    \nthe operations are properties of the return object, rather than items in \na
    results array. \n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to view the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestrictionbyoperation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/restrictions/master/_listings/atlassian/contentidrestrictionbyoperation-get-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---