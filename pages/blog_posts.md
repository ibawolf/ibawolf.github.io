---
layout: page
show_meta: false
title: "Blog Posts"
#subheadline: "Layouts of Feeling Responsive"
header:
  image_fullwidth: filegraduated-blue-backgroundpng-wikipedia-grey-blue-png-1000_500.png
permalink: "/blog_posts/"
---
<ul>
    {% for post in site.categories.blog_posts %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>