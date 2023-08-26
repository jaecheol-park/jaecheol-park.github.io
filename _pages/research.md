---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

You can also find my articles on <a href="https://scholar.google.com/citations?user=ifkgksAAAAAJ&hl=en&inst=17001591832933267808">my Google Scholar profile</a>.

<br/>

<h1> Working Papers/Work-in-Progress </h1>
{% for post in site.workingpapers reversed %}
  {% include archive-single.html %}
{% endfor %}

<br/>

<h1> Other Publications </h1>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
