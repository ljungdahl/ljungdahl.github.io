---
layout: home
image:
  feature: beachsquare2.jpg
permalink: /
title: " "
---

<img style="float: right; padding-left:50px;" src="images/profpic1.jpg" width="256">

### About
I am a PhD student in the [computational atomic physics](http://www.teori.atom.fysik.su.se/) group at [Stockholm University](http://www.fysik.su.se) (SU), working with professor Eva Lindroth in the area of attosecond physics.

On this site I try put some of my notes on physics and related things.
I also try to put up resources for my past and current teaching duties at SU.

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
