---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I’m Jan, an incoming Assistant Professor at The University of Texas at Austin, Austin in the Department of Aerospace Engineering & Engineering Mechanics. 

I’m an interpretive social scientist by training with a background in the humanities, but I have just enough expertise in computer science and data science to make trouble. My research, teaching, and broader service are all grounded in the idea that science and technology are inherently social activities, which are directed, operated, and maintained in certain ways (and not in other ways), by people in and outside of institutions.


This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. 




## News
======
<div style="overflow: auto; height:150pt; width:100%;">

 <style> #RecentNews li>p {display: inline;} </style>

    {% assign news = (site.data.news | sort: 'date') | reverse %} {% for n in news %}
    {{ n.date | date: "%B %-d, %Y" }}: {{ n.description | markdownify }}
    {% endfor %} 

UWDB Newsletters

    Summer 18
    [Winter 18]({{ site.baseurl }}/newsletters/winter18.pdf)
    [Summer 17]({{ site.baseurl }}/newsletters/summer17.pdf)
    [Fall 16]({{ site.baseurl }}/newsletters/fall16.pdf)


</div>



