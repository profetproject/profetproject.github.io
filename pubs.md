---
layout: default
title: Publications
---
<hr>

<table style="border: none">

<thead style="border: none">
  <tr style="border: none"><th colspan="3" style="border: none"><h4><a class="post-link">Publications</a></h4></th></tr>
</thead>

{% for post in site.pubs reversed %}

{% include pubentry.html %}

{% endfor %}
        
</table>