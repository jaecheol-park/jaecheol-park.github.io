---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}
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

