---
title: 010-directing-the-operation
permalink: 010-directing-the-operation.html
layout: page
unit:
    course: 'intro-operation-management'
    title: '010 Direction the operation'
    module: '000 Operation management'
---

## Content
The theoretical contents of the course are shown below.

{% assign files = site.static_files  %}
{% for file in files   %}
{% if file.path contains page.title and file.path contains  'pdf' %}
[{{ file.basename }}]( {{  site.baseurl }}{{ file.path }})
{% endif %}
{% endfor %}