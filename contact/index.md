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
  text="gu [at] njnu.edu.cn"
  link="gu@njnu.edu.cn"
%}
{%
  include button.html
  type="Office"
  text="Office 305, Mingli Hall, Xianlin Campus (Nanjing, Jiangsu)"
  link="https://www.google.com/maps/place/32°05'59.4%22N+118°54'36.8%22E/@32.0999703,118.9100622,20.39z/data=!4m7!1m2!2m1!1z5Y2X5Lqs5biI6IyD5aSn5a2m5LuZ5p6X5qCh5Yy65piO55CG5qW8!3m3!8m2!3d32.099843!4d118.910207?entry=ttu"
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
