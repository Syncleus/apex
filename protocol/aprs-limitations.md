---
title: APRS Limitations
sidebar: protocol_sidebar
permalink: /protocol/aprs-limitations/
toc: false
---

* Cant receive messages when beacon doesnt reach IGate.
* Current APRS networks break down during local disasters where internet in the local region is down.
* No discoverable way to access a stations capabilities such as coverage area, or cross-band capabilities.
* No universal and generic way to execute cross-band paths, critical in times of emergency.
* Lacks store-and-forward messaging capability
* No geographic routing, you must know an explicit path to your destination or use WIDE.
* Packets are naively repeated, no rate limiting mechenisms other than max distance.
* No automatic response to misbehaving stations, which can take down an entire local network.