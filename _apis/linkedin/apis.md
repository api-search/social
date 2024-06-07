---
name: LinkedIn
description: |-
  Welcome to LinkedIn, the world's largest professional network with more than
  950 million members in more than 200 countries and territories worldwide.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/linkedin.yml
created: 2023/11/23
modified: 2023/11/23
specificationVersion: '0.16'
tags: []
apis:
  - name: LinkedIn Consumer API
    description: >-
      The LinkedIn Consumer Solutions Platform enables sites and applications
      the power to enhance their sign-in experience using the world's largest
      professional network. The Consumer Solutions Platform contains APIs to
      Sign In with LinkedIn and Share on LinkedIn. Follow the links below to
      learn more about the Consumer Solutions Platform APIs.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.linkedin.com/product-catalog/consumer
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://learn.microsoft.com/en-us/linkedin/consumer/
      - type: Authentication
        url: >-
          https://learn.microsoft.com/en-us/linkedin/shared/authentication/authentication
      - type: Best Practices
        url: >-
          https://learn.microsoft.com/en-us/linkedin/shared/api-guide/best-practices/overview
      - type: Breaking Changes Policy
        url: >-
          https://learn.microsoft.com/en-us/linkedin/shared/breaking-change-policy
      - type: Errors
        url: >-
          https://learn.microsoft.com/en-us/linkedin/shared/api-guide/concepts/error-handling
      - type: Postman Workspace
        url: >-
          https://www.postman.com/linkedin-developer-apis/workspace/linkedin-consumer-solutions/overview
    overlays: []
    aid: linkedin:linkedin-consumer-api
  - name: LinkedIn Marketing API
    description: >-
      Grow your business by building scalable solutions that drive workflow
      efficiency, streamline marketing activities, deliver unique insights, and
      maximize results for B2B marketers.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.linkedin.com/product-catalog/marketing
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://learn.microsoft.com/en-us/linkedin/marketing/?view=li-lms-2023-11
      - type: Quickstart
        url: >-
          https://learn.microsoft.com/en-us/linkedin/marketing/quick-start?view=li-lms-2023-11
      - type: Authentication
        url: >-
          https://learn.microsoft.com/en-us/linkedin/shared/authentication/authorization-code-flow
      - type: Versioning
        url: >-
          https://learn.microsoft.com/en-us/linkedin/marketing/versioning?view=li-lms-2023-11
      - type: Whats New
        url: >-
          https://learn.microsoft.com/en-us/linkedin/marketing/integrations/recent-changes?view=li-lms-2023-11
    overlays: []
    aid: linkedin:linkedin-marketing-api
common:
  - type: Status
    url: https://www.linkedin-apistatus.com/
  - type: GitHub Organizations
    url: https://github.com/linkedin-developers
  - type: News
    url: https://www.linkedin.com/content/developers/news
  - type: Support
    url: https://www.linkedin.com/help/linkedin
  - type: Terms of Service
    url: https://www.linkedin.com/legal/l/api-terms-of-use
  - type: Type
    url: https://example.com
  - type: Privacy
    url: https://www.linkedin.com/legal/privacy-policy
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: linkedin
---