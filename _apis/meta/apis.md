---
name: Meta
description: >-
  Meta Platforms, Inc., doing business as Meta, and formerly named Facebook,
  Inc., and TheFacebook, Inc., is an American multinational technology
  conglomerate based in Menlo Park, California. The company owns and operates
  Facebook, Instagram, Threads, and WhatsApp, among other products and services.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/meta.yml
created: 2023/11/21
modified: 2023/11/21
specificationVersion: '0.16'
tags: []
apis:
  - name: Meta Graph API
    description: >-
      The Graph API is the primary way for apps to read and write to the
      Facebook social graph. All of our SDKs and products interact with the
      Graph API in some way, and our other APIs are extensions of the Graph API,
      so understanding how the Graph API works is crucial.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developers.facebook.com/docs/graph-api/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developers.facebook.com/docs/graph-api/
    overlays: []
    aid: meta:meta-graph-api
common:
  - type: Getting Started
    url: https://developers.facebook.com/docs/graph-api/get-started
  - type: Erros
    url: https://developers.facebook.com/docs/graph-api/guides/error-handling
  - type: Change Log
    url: https://developers.facebook.com/docs/graph-api/changelog
  - type: Explorer
    url: https://developers.facebook.com/tools/explorer/
  - type: Support
    url: https://developers.facebook.com/support/
  - type: Applications
    url: https://developers.facebook.com/apps/
  - type: Type
    url: https://example.com
  - type: Support
    url: https://developers.facebook.com/support/
  - type: Blog
    url: https://developers.facebook.com/blog/
  - type: Status
    url: https://metastatus.com/graph-api
  - type: Bugs
    url: https://developers.facebook.com/support/bugs/
  - type: Forum
    url: https://developers.facebook.com/community/
  - type: FAQ
    url: https://developers.facebook.com/support/faq/
  - type: Newsletter
    url: https://go.facebookinc.com/M4D-newsletter-subscription-signup.html
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: meta
---