---
layout: page
title: 
permalink: /
---


<table>
    <div class="featured-posts" 
    style="background-image:url({{ site.github.url }}/assets/img/StockSnap_TX6OSDXEC0.jpg">
    <h2><span>At KnowYourChapo our detection team works around the clock to spot Chapoposters</span></h2>
    </div>
</table>


<div style="width:75%;margin:0 auto;">
<font size = "5">
Welcome to <b>KnowYourChapo</b>. 
<br><br>
<h1><u>Who are we?</u></h1>
KnowYourChapo is a 501(c)(3) organization dedicated to the detecting, indexing, and removal of all <b>Chapoposters</b> from the internet. 

<br><br>
<h1><u>What is a Chapoposter?</u></h1>
A <b>Chapoposter</b> is a person who frequents the <b>r/ChapoTrapHouse subreddit</b>, a community known for encouraging <b>violence, bigotry, and harmful ideologies.</b>

<br><br>
<h1><u>What can I do to help?</u></h1>
You can help by <b>downvoting, calling out, and discouraging</b> Chapoposters from being anywhere on the internet. 
</font>
</div>



<br><br>



{% assign chapolist = site.data.chapolist.chapos %}
<table style="width:75%; margin:0 auto;">

<center>
<h1>List of known Chapoposters</h1>
</center>
<br>

<tr>
    <!-- <td><h1>Username</h1></td> -->
    <!-- <td><h1>Notes</h1></td> -->
</tr>

{% for chapo in chapolist %}

  	<tr>
	    <td><a href="http://www.reddit.com/u/{{chapo.name}}">{{chapo.name}}</a></td>
	    <!-- <td>{{chapo.notes}}</td> -->
  	</tr>

{% endfor%}
</table>



