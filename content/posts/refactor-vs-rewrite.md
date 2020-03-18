---
title: "Refactor vs Rewrite"
description: ""
date: 2020-03-09T10:00:00-05:00
categories: [ "roadmap" ]
author: "Kevin Jordan"
tags: ["code", "roadmap"]
draft: true
---

TODO: insert TLDR at top

TODO: insert video

I originally wrote Squid Alerts because I wanted a cheaper, more user friendly on-call management tool. It's grown slowly because after I finished the initial features, I was hesitant to add anything else. To be completely honest, I didn't know how I could beat the competition. There quite a few well established incident management tools out in the marketplace and while I wasn't trying to build a billion dollar company, I wanted to offer something unique in the marketplace. Not just another clone. Plus since I'd rather build cool stuff then sell it, I needed my product to speak for itself.

Recently, I came up with the four key pillars and felt like I finally had an original value proposition.
1. Security & Trust
2. Ownership & Transparency
3. Intelligence
4. Custom Obsession

With these pillars, came a new vision for the product. Part of this vision is actually the driving factor behind this blog (trust + transparency), but with it also came a laundry list of features, redesigned API, and a maturation of coding practices. (FYI, the current code base has 42% unit test coverage).

Notes:
- Moving to .Net Core 3.1
- Reduce complexity (away from domain driven, too many folders / hard to find stuff, multiple authentication systems)
- Moving from Mongo to MariaDB (my data is more relational)
- More strict coding standards. With customers need to do better testing, documentation, performance, security).
- Incidents, not alerts, will take over as the primary object. 
- API first? 


