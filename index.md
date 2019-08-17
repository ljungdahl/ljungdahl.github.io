---
layout: home
image:
  feature: beachsquare.jpg
permalink: /
title: " "
---

---

<img style="float: right; padding-left:50px;" src="images/profpic1.jpg" width="256">

### About
I am a PhD student in [computational atomic physics](http://www.teori.atom.fysik.su.se/) at Stockholm University, in the group of professor Eva Lindroth. My thesis subject is in the area of "attosecond chronoscopy", where we study temporal aspects of photoionisation.

---

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
