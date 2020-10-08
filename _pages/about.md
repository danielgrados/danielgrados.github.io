---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify">   

I am a <strong>research <strong>scientist at <strong><Marine Institute of the Sea - IMARPE> in the field of <strong>Data Science and Marine Biology</strong>. I am quite involved in interdisciplinary research at the <strong>interface between data science and marine ecology</strong>. My current research interests include <strong>deep and machine learning applications to understanding marine resources.<br>  

<!--</div>
<div style="text-align: justify">-->
</div>

## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
