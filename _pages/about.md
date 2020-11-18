---
permalink: /
title: "Heng-Chien Liou"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I'm an undergraduate student in National Taiwan University, with double major in Electrical Engineering and Psychology. 

My learning and research experiences span across many disciplines. Currently, my works focus on Network Science and Computational Social Science. 

Here is my [curriculum vitae](https://leohcliou.github.io/files/CV20200511.pdf)

# Publications

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=exOp9McAAAAJ">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}





