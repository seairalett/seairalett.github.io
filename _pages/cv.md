---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
lang: en
redirect_from:
  - /resume
---
<ul>
{% assign posts=site.posts | where:"ref", page.ref | sort: 'lang' %}
{% for post in posts %}
  <li>
    <a href="{{ post.url }}" class="{{ post.lang }}">{{ post.lang }}</a>
  </li>
{% endfor %}

{% assign pages=site.pages | where:"ref", page.ref | sort: 'lang' %}
{% for page in pages %}
  <li>
    <a href="{{ page.url }}" class="{{ page.lang }}">{{ page.lang }}</a>
  </li>
{% endfor %}
</ul>

{% include base_path %}
<br>
<div class="cv-download-links">
  <a href="{{ base_path }}/files/CV.pdf" class="btn btn--primary">Download full CV here</a>
</div>
<br>

Education
======
* PhD in linguistics, University of Georgia, 2027 (expected)
* Master of Education, University of Missouri-St. Louis
* BA in Spanish & linguistics, Emory University

Teaching
======
* Teaching Assistant, University of Georgia, 2022-2026

* Workshop facilitator, Institute on Collaborative Language Research, University of Nevada, summer 2026

* Spanish-English kindergarten teacher, Carver Dual Language School, Kansas City, MO, 2020-2022

* Facilitator, Amigos de las Américas, 2021
  
Languages
======
* English, native
* Spanish, near-native
* Portuguese, intermediate
* Japanese, intermediate
* Chuj, conversational & linguistic knowledge

