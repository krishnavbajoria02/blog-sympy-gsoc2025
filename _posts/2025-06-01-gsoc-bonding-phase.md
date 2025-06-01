---
layout: post
title: "GSoC Bonding Phase"
date: 2025-06-01
---

This phase I began extensively deep diving into exploring SymPy’s assumptions system, researching and understanding implementations of SAT solvers and SAT handlers.

Besides this, I have been working on fixing the first couple of issues which were low-hanging fruit as listed in my proposal:
- Equivalence of `Q.eq(x, 0)` and `Q.zero(x)`
- `Q.ge(x)` implying `Q.gt(x)`
- `Q.le(x)` implying `Q.lt(x)`

Excited to start pushing more code soon 🚀.
