---
layout: pattern
title: Caching
folder: caching
permalink: /patterns/caching/
categories: Other
tags:
 - Java
---

**Intent:** To avoid expensive re-acquisition of resources by not releasing
the resources immediately after their use. The resources retain their identity, are kept in some
fast-access storage, and are re-used to avoid having to acquire them again.

![alt text](./etc/caching.png "Caching")

**Applicability:** Use the Caching pattern(s) when

* Repetitious acquisition, initialization, and release of the same resource causes unnecessary performance overhead.

**Credits**

* [Write-through, write-around, write-back: Cache explained](http://www.computerweekly.com/feature/Write-through-write-around-write-back-Cache-explained)
* [Read-Through, Write-Through, Write-Behind, and Refresh-Ahead Caching](https://docs.oracle.com/cd/E15357_01/coh.360/e15723/cache_rtwtwbra.htm#COHDG5177)
