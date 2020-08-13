---
title: "Normale Cacheable Page"
date: 2020-08-10T18:20:27+02:00
lastmod: 2020-08-13T18:20:27+02:00
publishdate: 2020-08-10T18:20:27+02:00
description: "Normale Cacheable Page"
categories: ["Content-Type"]
---
## Basic description:
The "usual" page is something that do not change much when published and can be cached in a CND or in the user browser.
As caching is a notoriously complex topic, it is not we are not going to discuss cache policy.

## Headers

| header | example value | Description |
| ------ | ----------- | ----------- |
| [Content-Type]({{< ref "/headers/content-type" >}}) | text/html; charset=UTF-8 | The document is a html and the character encoding is UTF-8 |
| [Etag]({{< ref "/headers/etag" >}}) | meaningleshash | A hash of the content |
