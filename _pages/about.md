---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br />
　　I am currently a professor with the School of Software Engineering at South China University of Technology. I received my Bachelor Degree in Environmental Science and Engineering in 2006 and Master degree in Control Science and Engineering in 2009, both from Hunan University in Changsha, China. I received the Ph.D. degree in Computer Science from Nanyang Technological University, Singapore, in 2014. From 2014-2016, I worked as a Senior Research Associate on computer vision in the School of Computer Science, University of Adelaide, Australia. My research interests include machine learning, sparse analysis, deep learning and large-scale optimization.


Join us
---
<br />
　　Our research group still has two academic doctoral places (application examination system), the research interests include large model, embodied intelligence (intelligent robot), etc. Please contact me via email for interested students mingkuitan@scut.edu.cn.


Conferences
----------
<div>
  <table>
  {% for post in site.conferences_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/conferences/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


Journals
----------
<div>
  <table>
  {% for post in site.journals_main reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
   <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>

<!-- <div margin-bottom:100px>
  <a href="/journals/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div>  -->


Preprint Paper
----------
<div>
  <table>
  {% for post in site.preprints reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

