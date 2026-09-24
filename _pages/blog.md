---
permalink: /blog/
title: "Case Studies"
excerpt: "Decision-oriented examples of where margin leaks, trapped cash, and operational waste show up—and what operators can do about it."
layout: single
author_profile: true
---

These are outcome and decision-clarity examples for operators — not a data-science portfolio. Each one shows where margin leaks, trapped cash, or operational waste shows up in a real business model, and what an operator could do about it. Healthcare and ops-margin examples first; other verticals show the same decision-support pattern.

If you're wondering whether this kind of work fits your situation, take the [Margin Leak Check](/leak-check/) or [book a free Fit Call](/audit/).

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
**{{ post.date | date: "%B %d, %Y" }}**  
{{ post.excerpt | markdownify }}

{% endfor %}
