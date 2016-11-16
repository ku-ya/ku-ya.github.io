---
title: "Publications: by type"
modified: 2016-01-12
permalink: /publications/type/
---

{% include base_path %}

Sort by: [year](/publications/), [subject](/publications/subject)  
[Google Scholar](https://scholar.google.com/citations?user=yU33tGsAAAAJ&hl=en&oi=ao)

## JOURNAL

{% bibliography group_by: type, year --query @article %}

## CONFERENCE PROCEEDING

{% bibliography group_by: type, year --query @inproceedings %}
