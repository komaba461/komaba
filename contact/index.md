---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

再次感谢对本课题组以及我个人研究方向对兴趣，若想了解跟多或者更多了解，你也可以随时跟我联系。
也欢迎来南师大我办公室跟我谈，我的地点在：*南京市文苑路1号南京师范大学仙林校区 明理楼305室*。 
当然也欢迎方便的时候给我写email，这个是最方便的了~

{%
  include button.html
  type="email"
  text="gu@njnu.edu.cn"
  link="gu@njnu.edu.cn"
%}
{%
  include button.html
  type="phone"
  text="136-7516-1540"
  link="+86-136-7516-1540"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/南京师范大学仙林校区/@32.1145815,118.9135141,17z/data=!3m1!4b1!4m6!3m5!1s0x35b5ec3014a1e7f5:0x197121e642a7bf08!8m2!3d32.114577!4d118.916089!16s%2Fg%2F1vy7dm_q?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/gyh_with_ kitsure.jpg"
  caption="Yanhui with KITSUREGAWA"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/zzh_invited_talk.jpg"
  caption="Invited Talk by Zhihua Zhou"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Artificial Intelligence 
{% endcapture %}

{% capture col2 %}
Biochemistry and Biomedicine
{% endcapture %}

{% capture col3 %}
AI for Science
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
