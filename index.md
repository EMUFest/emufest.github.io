---
layout: home
title: EMUFest 2015
excerpt: "International Electroacoustic Music Festival"
search_omit: true
image:
  feature: banners/2012-bertoncini_crop.png
  credit: Giuseppe Silvi
  creditlink: http://www.giuseppesilvi.com
---

**Conservatorio Santa Cecilia**

<div markdown="0">
  <a href="{{site.url }}/schedule/#october-5th"
    class="btn">OCTOBER 5th</a>
  
  <a href="{{site.url }}/schedule/#october-6th"
    class="btn">OCTOBER 6th</a>
  
  <a href="{{site.url }}/schedule/#october-7th"
    class="btn">OCTOBER 7th</a>    
  
  <a href="{{site.url }}/schedule/#october-8th"
    class="btn">OCTOBER 8th</a>
  
  <a href="{{site.url }}/schedule/#october-9th"
    class="btn">OCTOBER 9th</a>
</div>

**University of Rome Tor Vergata**

<div markdown="0">  
  <a href="{{site.url }}/schedule/#october-13th"
    class="btn">OCTOBER 13th</a>
  
  <a href="{{site.url }}/schedule/#october-13th"
    class="btn">OCTOBER 14th</a>
                  
</div>

---

<h3>Latest EMUFest News:</h3>

<ul class="post-list">
{% for post in site.categories.articles limit:5 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul>

<!-- <h3>Blog Posts:</h3>

<ul class="post-list">
{% for post in site.categories.blog limit:5 %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>{% if post.excerpt %} <span class="excerpt">{{ post.excerpt }}</span>{% endif %}</a></article></li>
{% endfor %}
</ul> -->