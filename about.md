---
layout: page
title: About
permalink: /professional/about
section: professional
---

<div class="about-layout">
  <div class="about-photo">
    <img src="{{ '/assets/professional/portrait.png' | relative_url }}" alt="Philip Ekholm" />
  </div>
  <div class="about-text">
{% assign birth_year = 1996 %}
<!-- Accurate enough, my b-day is 30th of Dec, so 363 days a year it'll correctly display my age-->
{% assign age = 'now' | date: '%Y' | minus: birth_year | minus: 1 %}

<h2>Hej, and welcome to my site!</h2>

<p>My name is Philip Ekholm. I'm a {{ age }}-year-old IT-consultant based in Malmö, Sweden, currently working at Sigma Technology Cloud. I enjoy building things that last, and I love problem solving!</p>

<p>Outside of work, I spend my time on side projects, road trips across Scandinavia, and exploring new technologies. I'm drawn to simplistic design, software that lasts, and solving interesting problems.</p>

<h2>What I do</h2>

<p>I currently work as an IT-consultant where I specialize in Cloud Computing. I have several years experience in particularly Google Cloud.</p>

<h2>Get in touch</h2>

<p>Feel free to reach out via <a href="mailto:philipekholm@protonmail.com">email</a> or connect with me on <a href="https://www.linkedin.com/in/philip-ekholm-6543a114b/" target="_blank" rel="noopener">LinkedIn</a> and <a href="https://github.com/PhilipEkholm" target="_blank" rel="noopener">GitHub</a>.</p>

  </div>
</div>
