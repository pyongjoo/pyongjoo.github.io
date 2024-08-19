---
layout: post
title: "VerdictDB: Universal Approximate Query Processing"
---

<img src="/resources/projects/verdictdb.png" width="500px" class="center-block" />

Despite 25 years of research in academia, approximate query processing (AQP) has had little industrial adoption,
mostly due to the reluctance of traditional vendors to make radical changes
and also due to the tight integration with specific platforms.

Our proposal, called VerdictDB, uses a middleware architecture that requires no changes to the backend database, and thus, can work with all off-the-shelf engines. Operating at the driver-level, VerdictDB intercepts analytical queries issued to the database and rewrites them into another query that, if executed by any standard relational engine, will yield sufficient information for computing an approximate answer. VerdictDB uses the returned result set to compute an approximate answer and error estimates, which are then passed on to the user or application. However, lack of access to the query execution layer introduces significant challenges in terms of generality, correctness, and efficiency.

<p class="post-continue" style="margin-top: 40px;">
	<a href="https://verdictdb.org">Find more from a project home &rarr;</a>
</p>
