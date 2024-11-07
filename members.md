---
layout: default
title: Members
---
<div class="copy">
	<div class="copy">
		<div>
<hr>
 {% for member in site.data.members %}

	<img src="/assets/img/{{ member.pic }}" style="margin-top:0px; margin-bottom:5px; margin-right:10px; float:left; width:150px !important">
	<h4>{{ member.name }}</h4>
	<h5>{{ member.role }} / {{ member.institute }}</h5>
	<span class="social-share-googleplus"><a href="https://twitter.com/{{member.twitter}}" title="Twitter" class="fa fa-twitter" style="height:20px"></a></span>
	<span class="social-share-googleplus"><a href="{{member.web}}" title="Web" class="fa fa-globe" style="height:20px"></a></span>
	<br>

	 <p class="copy" align="justify">{{ member.cv }}</p>
<hr>
{% endfor %}

<h4>Previous Members</h4>
<hr>
 {% for prevmember in site.data.prevmembers %}

	<img src="/assets/img/{{ prevmember.pic }}" style="margin-top:0px; margin-bottom:5px; margin-right:10px; float:left; width:150px !important">
	<h4>{{ prevmember.name }}</h4>
	<h5>{{ prevmember.role }} / {{ prevmember.institute }}</h5>
	<span class="social-share-googleplus"><a href="https://twitter.com/{{prevmember.twitter}}" title="Twitter" class="fa fa-twitter" style="height:20px"></a></span>
	<span class="social-share-googleplus"><a href="{{prevmember.web}}" title="Web" class="fa fa-globe" style="height:20px"></a></span>
	<br>

	 <p class="copy" align="justify">{{ prevmember.cv }}</p>
<hr>
{% endfor %}

</div>
</div>
</div>


