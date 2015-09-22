---
layout: default
title: A Collection of Interesting Tidbits About Sept 22
---

# A Collection of Interesting Tidbits About Sept 22

## By: GitHub Student

{% for post in site.posts %}
  * {{ post.date | date: "%b %-d, %Y" }} - **[{{ post.title}}]({{ post.url | prepend: site.baseurl }})**
{% endfor %}
