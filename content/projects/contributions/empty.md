---
title: "Empty"
link: "Empty"
image: "Empty"
description: "Empty"
featured: true
tags: ["Tag1","Tag2"]
fact: "Empty"
weight: 100
sitemap: 
    priority : 0.8
---

Addressed pretty significant page load performance issue founde in larger deployments. Eliminates uses of intensive backend query, replacing it with an asynchronous API call against a lucene index. This change reduces page load from from 2+ minutes to nearly instant, with an incredibly responsive UI.
