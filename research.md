---
title: Research
layout: default
permalink: /research/
---

# Research

My research interests include leveraging **Deep Learning** and **Natural Language Processing** techniques to solve real-world problems in the fields of **Software Engineering** and **Security**. Looking forward, I am also open to studying more human-centric problems from **Human-AI Interaction**, **AI for Society and Healthcare** domains.

---

## Ongoing

{% for post in site.posts %}
{% if post.status == 'ongoing' %}
{% for cat in post.categories %}
{% if cat == 'research' %}
<div class="entry-row">
  <div class="entry-thumb">
    <img src="/tn{{ post.image }}" alt="{{ post.title }}">
  </div>
  <div class="entry-body">
    <h3>{{ post.title }}</h3>
    {{ post.authors }}
    <br>
    <em class="venue-tag">{{ post.venue }}</em>, {{ post.date | date: "%Y" }} <strong class="honor-tag">{{ post.honor }}</strong>
    <br>
    <span class="entry-links">
      {% if post.arxiv %}<a href="{{ post.arxiv }}" target="_blank">paper</a> /{% endif %}
      {% if post.abstract %}<a href="{{ post.abstract }}" target="_blank">abstract</a> /{% endif %}
      {% if post.proposal %}<a href="{{ post.proposal }}" target="_blank">proposal</a> /{% endif %}
      {% if post.code %}<a href="{{ post.code }}" target="_blank">code</a> /{% endif %}
      {% if post.poster %}<a href="{{ post.poster }}" target="_blank">poster</a> /{% endif %}
      {% if post.slides %}<a href="{{ post.slides }}" target="_blank">slides</a> /{% endif %}
      {% if post.video %}<a href="{{ post.video }}" target="_blank">video</a> /{% endif %}
      {% if post.youtube %}<a href="{{ post.youtube }}" target="_blank">youtube</a> /{% endif %}
      {% if post.website %}<a href="{{ post.website }}" target="_blank">website</a> /{% endif %}
    </span>
    <p>{{ post.excerpt }}</p>
    <span class="entry-sup">Supervisor(s):</span> {{ post.sup }}
  </div>
</div>
{% endif %}
{% endfor %}
{% endif %}
{% endfor %}

---

## Completed

{% for post in site.posts %}
{% if post.status == 'completed' %}
{% for cat in post.categories %}
{% if cat == 'research' %}
<div class="entry-row">
  <div class="entry-thumb">
    <img src="/tn{{ post.image }}" alt="{{ post.title }}">
  </div>
  <div class="entry-body">
    <h3>{{ post.title }}</h3>
    {{ post.authors }}
    <br>
    <em class="venue-tag">{{ post.venue }}</em>, {{ post.date | date: "%Y" }} <strong class="honor-tag">{{ post.honor }}</strong>
    <br>
    <span class="entry-links">
      {% if post.arxiv %}<a href="{{ post.arxiv }}" target="_blank">paper</a> /{% endif %}
      {% if post.abstract %}<a href="{{ post.abstract }}" target="_blank">abstract</a> /{% endif %}
      {% if post.proposal %}<a href="{{ post.proposal }}" target="_blank">proposal</a> /{% endif %}
      {% if post.code %}<a href="{{ post.code }}" target="_blank">code</a> /{% endif %}
      {% if post.poster %}<a href="{{ post.poster }}" target="_blank">poster</a> /{% endif %}
      {% if post.slides %}<a href="{{ post.slides }}" target="_blank">slides</a> /{% endif %}
      {% if post.video %}<a href="{{ post.video }}" target="_blank">video</a> /{% endif %}
      {% if post.youtube %}<a href="{{ post.youtube }}" target="_blank">youtube</a> /{% endif %}
      {% if post.website %}<a href="{{ post.website }}" target="_blank">website</a> /{% endif %}
    </span>
    <p>{{ post.excerpt }}</p>
    <span class="entry-sup">Supervisor(s):</span> {{ post.sup }}
  </div>
</div>
{% endif %}
{% endfor %}
{% endif %}
{% endfor %}


<style>
.entry-row {
  display: flex;
  gap: 20px;
  margin-bottom: 28px;
  align-items: flex-start;
  border-bottom: 1px solid #f0f0f0;
  padding-bottom: 20px;
}
.entry-thumb {
  flex: 0 0 150px;
  max-width: 150px;
}
.entry-thumb img {
  width: 100%;
  height: auto;
  border-radius: 5px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.08);
}
.entry-body h3 {
  color: darkblue;
  margin-bottom: 5px;
  font-size: 0.98em;
  text-align: left;
}
.venue-tag { color: darkgreen; }
.honor-tag { color: red; }
.entry-links a { margin-right: 4px; }
.entry-sup { color: darkblue; font-weight: 600; }
@media (max-width: 600px) {
  .entry-row { flex-direction: column; }
  .entry-thumb { max-width: 100%; }
}
</style>
