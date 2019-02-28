---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site.

<h2>Publications</h2>
{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}

<h2>Research</h2>
{% for post in site.research %}
  {% include archive-single.html %}
{% endfor %}

<h2>CV</h2>
{% for post in site.pages.cv %}
  {% include archive-single.html %}
{% endfor %}

<h2>Contact</h2>
{% for post in site.pages.markdown %}
  {% include archive-single.html %}
{% endfor %}