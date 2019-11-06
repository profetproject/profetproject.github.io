---
layout: default
title: Publications
---
<hr>

<table class="pubtable">

<thead >
  <tr ><th colspan="3" ><h4><a class="post-link">Publications</a></h4></th></tr>
</thead>

{% for post in site.pubs reversed %}

{% include pubentry.html %}

{% endfor %}
        
</table>