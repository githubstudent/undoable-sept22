
# A Collection of Interesting Tidbits About Sept 22

## By: GitHub Student (@jaw6)

{% include base.html %}
{% for post in site.posts %}
  * {{ post.date | date: "%b %-d, %Y" }} - **[{{ post.title}}]({{ post.url | prepend: base }})**
{% endfor %}
