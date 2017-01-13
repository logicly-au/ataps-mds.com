---
title: Announcements
page-name: announcements
sub-heading: Announcements
---
<h1>Announcements</h1>
<p>This page documents announcements that have been issued for the Minimum Data Set (MDS).</p>
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="#{{ post.url }}">{{ post.title }}</a><span> | {{ post.date | date: '%B %d, %Y' }}</span>
    </li>
  {% endfor %}
  <li>
      <a href="/mds/announcements/all/index.html">Older Posts...</a>
  </li>
</ul>

<hr />
<div>
<ul class="l-communications-ul">
  {% for post in site.posts %}
    <li class="l-communications">
    <div id = "{{ post.url }}"><h3>{{ post.title }}</h3></div>
    <h4>{{ post.date | date: '%B %d, %Y' }}</h4>
	{{ post.content }}
	<hr />
</li>
  {% endfor %}
</ul>
</div>
