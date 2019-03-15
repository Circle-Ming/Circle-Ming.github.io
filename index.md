---
layout: page
title: About me
cover: false
---

I am a undergraduate research student in the Artificial Intelligence 
Institute in the [School of Computer Science and Technology](http://www.cs.zju.edu.cn/)
at the [Zhejiang University](http://www.zju.edu.cn/). I am advised by 
[Siliang Tang](https://person.zju.edu.cn/siliang) in ZJUAI/[DCD](http://www.dcd.zju.edu.cn/). 

I am broadly interested in connecting natural language with real world 
scenarios, and using them to guide natural language understanding.

## News


## Current Research Highlights

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

