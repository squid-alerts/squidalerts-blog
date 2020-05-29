---
title: "Designing Resilient Web Applications on a Budget"
description: ""
date: 2020-05-29T10:00:00-05:00
categories: [ "engineering" ]
author: "Kevin Jordan"
tags: ["reliability", "security"]
draft: true
---

TODO: insert TLDR at top

TODO: insert video

1. Architecture diagram
2. IaaS > PaaS
  a. Saving money with reserved instances
3. Achieving the 9s (multi server / multi region / multi cloud)
4. Moving to MariaDB for performance and cost (and more relational data)
  a. Galera multi master replication
5. Cloudflare (load balancer) - cheap, hosting agnostic, free SSL
  a. CDN (performance?)
6. Backups
7. Monitoring
8. Deployment processes
9. (Should this be moved to a performance post?) Moving to linux for performance and cost
10. (Should this be moved to a performance post?) Picking a fast language - and one that I know well (C# / .NET Core)
11. (Should this be moved to a performance post?) Keeping static pages, static (landing pages, api documentation, blog)
12. (Should this be moved to a performance post?) Avoiding SPA, progressively reducing javascript libraries
