---
title: "Critical MongoDB Flaw Allows Unauthenticated Attackers to Crash Database Servers, Trigger RCE"
source: "CyberPress"
source_url: "https://cyberpress.org/critical-mongodb-flaw/"
published_at: "2026-11-12T12:28:20.000Z"
published_at_central: "Nov 12, 2026, 5:58:20 PM"
created_at: "2026-11-13T06:30:23.708Z"
created_at_central: "Nov 13, 2026, 12:00:23 PM"
timezone: "America/Chicago"
tags:
  - cyber
  - vulnerability
---
MongoDB has patched a critical use-after-free memory-corruption defect, tracked as CVE-2026-118383, that carries a CVSS v4.0 score of 9.5. Unauthenticated network requests can trigger it in the replication component of MongoDB Server. The result can be an abrupt server termination or, under certain conditions, arbitrary code execution in the server process. 
[Read the full post](https://cyberpress.org/critical-mongodb-flaw/)
Processed: Nov 13, 2026, 12:00:23 PM (Central)