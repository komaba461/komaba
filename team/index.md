---
title: Team
nav:
  order: 3
  tooltip: About our team
---


<!-- section dark -->
<!-- section background images/banner.jpg -->

{% include figure.html image="images/2023-graduate.jpg" width="80%" %}

We are looking for motivated students interested in the intersection of Computer Science, Artificial Intelligence,
and Natural Science.

<!-- PhD applicants may apply through Nanjing Normal University graduate admissions, being sure to note Yahui Gu as their primary faculty member of interest. -->

Postdoctoral applicants, masters students, and undergraduates should reach out to Prof. Gu directly, being sure to include area of interest, time frame, and the type of work (Masters thesis, general research, etc). 
<!-- Applicants may wish to identify a PhD student whose interests align with theirs, who could supervise. -->

{%
  include big-link.html
  icon="fas user-graduate"
  text="Master Applicants"
  link="http://ceai.njnu.edu.cn/Item/list.asp?id=1638"
  button=true
%}{%
  include big-link.html
  icon="fas envelope"
  text="Other Applicants"
  link="mailto:unberath@jhu.edu"
  button=true
%}{:.center}

<!-- section break -->


# {% include icon.html icon="fa-solid fa-users" %}Team

Our team consists of full-time PhD students, Masters students, and undergrads, led by Prof. Yanhui Gu. For up-to-date info on our members, check out their personal websites, Google Scholar profiles, or social media by clicking through below.



{% include section.html %}
{% capture contents %} 
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: programmer" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: master, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: " %}

{% endcapture %}

{% include centerer.html contents=contents %}

<!-- ## Graduate Student
{% capture contents %} 
{% endcapture %}
{% include centerer.html contents=contents %}

## Undergraduate Student
{% capture contents %} 
{% endcapture %}
{% include centerer.html contents=contents %} -->


## Alumni

{% capture contents %} 
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: master, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: mascot, group: alum" %}
{% endcapture %}

{% include centerer.html contents=contents %}

