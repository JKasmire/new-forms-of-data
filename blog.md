---
layout: default
title: Blog
---

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ http://blog.ukdataservice.ac.uk/new-forms-of-data/ }}">{{ Hello! My Name is… New Forms of Data! }}</a></h2>
      {{ As a new addition to the UK Data Service, I would like to start by introducing myself. My name is actually Julia Kasmire and I am the Research Fellow leading UK Data Service’s new training programme on New Forms of Data.

“But what is ‘New Forms of Data’?!?” I hear you cry.

You are right to do so.

New Forms of Data is the cool new way to talk about Big Data. There is every reason to hope that New Forms of Data will be a more inclusive concept (size is not everything, man!) but only time will tell. }}
    </li>
  {% endfor %}
</ul>
