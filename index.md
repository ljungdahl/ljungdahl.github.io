---
layout: home
image:
  feature: beachsquare2.jpg
permalink: /
title: " "
---

<img style="float: right; padding-left:50px;" src="images/profpic1.jpg" width="256">

### About
I am a PhD student in the [computational atomic physics](http://www.teori.atom.fysik.su.se/) group at [Stockholm University](http://www.fysik.su.se) (SU), specifically in the group of professor Eva Lindroth.

Before going back to university to study physics I spent five years as a technical artist in the visual effects/computer graphics industry.

Here I put some of my notes on maths/physics of varying length and level, and resources for my past and current teaching assistant duties at SU.

### Research interests
My thesis subject is in the area of "attosecond physics", or just "attophysics", which might be broadly described as the study of phenomena that occur on an attosecond  timescale (that is 10<sup>-18</sup> seconds). We are in particular looking at electron dynamics of light-matter interaction (eg photoionisation). As theorists our primary tools to study this are in-house developed codes and pen and paper.

Apart from my thesis work and science in general I am interested in things like graphics programming, music and the visual arts.

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
