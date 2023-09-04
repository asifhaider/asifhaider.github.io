---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am <b> Md. Asif Haider </b> (you can simply call me <b>Asif</b>) from <b>Dhaka, Bangladesh</b>. I am a passionate undergraduate student with a never-ending interest in science and arts. Into learning new things about technology and research with a view to solving engineering problems. Currently studying <b>Computer Science and Engineering</b> as major at <b>Bangladesh University of Engineering and Technology (BUET)</b> in my senior (fourth) year.

I am looking for <b>Research Assistant</b> positions in Computer Science and Engineering research labs and <b>Intern/Part-time</b> positions in Software Engineering industry. You can also knock me with mentoring and content creation opportunities.

## News and Updates

{% assign latest_news_limit = 2 %}

{% for limit: latest_news_limit %}
  {% if forloop.index <= latest_news_limit %}
    <p style="color: blue;">
  {% else %}
    <p>
  {% endif %}
    - **{{ item.date }}**: {{ item.news }} <a style="text-decoration: none" href="{{ item.link }}">Details</a>
    </p>
{% endfor %}

- **March, 2023**: Got promoted to Vice-chairperson (Strategey) at the IEEE Computer Society BUET Student Branch Chapter. <a style="text-decoration: none" href="https://www.facebook.com/ieeebuetcs/posts/pfbid0rNvtGvX2erYjvMYQba8F739BVo5ZS2Hsrvd1ZuafpcgqeKSraMzzyEtre5uUDHx7l">Details</a>
- **December, 2022**: Presented student research poster at the <a style="text-decoration: none" href="https://cse.buet.ac.bd/nsyss2022/"> 9th NSysS 2022</a> held at Cox's Bazar. <a style="text-decoration: none" href="https://www.linkedin.com/feed/update/urn:li:activity:7013882466746720256/">Details</a>
- **November, 2022**: Visited Dallas, Texas, USA to attend the <a style="text-decoration: none" href="https://sc22.supercomputing.org/">SC22 conference</a> with ACM <a style="text-decoration: none" href="https://www.sighpc.org/for-our-community/hpc-immersion">HPC Immersion</a> Travel Grant. <a style="text-decoration: none" href="https://www.linkedin.com/posts/asif-haider-1805112_sc22-highperformancecomputing-hpcaccelerates-activity-7004850310015848448-7bkh?utm_source=share&utm_medium=member_desktop">Details</a>


**Last updated:** September 2023