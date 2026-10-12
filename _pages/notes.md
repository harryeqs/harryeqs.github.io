---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

A collection of **revision notes** I put together during my fourth year at Cambridge (Engineering Part IIB), organised around key topics for Tripos preparation. These notes cover the 2025–2026 versions of the courses. They are concise summaries rather than comprehensive course notes, and may contain errors or omissions. Please feel free to contact me if you spot any errors or have any questions.

The TeX files can be accessed at [https://github.com/harryeqs/Part-IIB-Notes](https://github.com/harryeqs/Part-IIB-Notes).

{::nomarkdown}
{% assign notes = site.notes | sort: "title" | sort: "module" %}
{% for post in notes %}
  {% include archive-single.html %}
{% endfor %}
{:/nomarkdown}
