---
title: Short writing by Adam Lloyd
layout: index

---

## Short things I've written

### Short Stories
{% for post in site.categories.story reversed %}
 * [{{post.title}}]({{site.baseurl}}{{post.url}})&mdash;{{post.date|date_to_long_string}}
{% endfor %}

### Poetry
{% for post in site.categories.poetry reversed %}
 * [{{post.title}}]({{site.baseurl}}{{post.url}})&mdash;{{post.date|date_to_long_string}}
{% endfor %}
