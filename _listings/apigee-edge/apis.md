---
name: Apigee Edge
x-slug: apigee-edge
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Deployments
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Deployments
  x-api-slug: apigee-edge
  description: Gets all deployments of an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/deployments
  tags: Organizations,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name Deployments
  x-api-slug: apigee-edge
  description: Gets the deployments for an environment in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/deployments
  tags: Organizations,Environments,Env,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameenvironmentsenv-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameenvironmentsenv-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name API Name Deployments
  x-api-slug: apigee-edge
  description: Gets the deployments for an API Proxy in the given environment in an
    organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/apis/{api_name}/deployments
  tags: Organizations,Environments,Envs,APIs,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameenvironmentsenv-nameapisapi-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameenvironmentsenv-nameapisapi-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name API Name Revisions
    Revision Number Deployments
  x-api-slug: apigee-edge
  description: "Gets the deployments for an API Proxy\xE2\x80\x99s revision for an
    environment in an organization."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/apis/{api_name}/revisions/{revision_number}/deployments
  tags: Organizations,Environments,Envs,APIs,Revisions,Revision,Number,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameenvironmentsenv-nameapisapi-namerevisionsrevision-numberdeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameenvironmentsenv-nameapisapi-namerevisionsrevision-numberdeployments-get-openapi.md
- name: Apigee Edge Post Organizations Name API Name Revisions Revision Number Deployments
  x-api-slug: apigee-edge
  description: Undeploys an API proxy revision from an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apis/{api_name}/revisions/{revision_number}/deployments
  tags: Organizationss,APIs,Revisions,Revision,Number,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameapisapi-namerevisionsrevision-numberdeployments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameapisapi-namerevisionsrevision-numberdeployments-post-openapi.md
- name: Apigee Edge Get Organizations Name API Name Deployments
  x-api-slug: apigee-edge
  description: Returns detail on deployments of the API specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apis/{api_name}/deployments
  tags: Organizationss,APIs,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameapisapi-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameapisapi-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name API Name Revisions Revision Name Deployments
  x-api-slug: apigee-edge
  description: Get deployments for a revision of an API proxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apis/{api_name}/revisions/{revision_name}/deployments
  tags: Organizationss,APIs,Revisions,Revision,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameapisapi-namerevisionsrevision-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/organizationsorg-nameapisapi-namerevisionsrevision-namedeployments-get-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/deployments/master/_listings/apigee-edge/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---