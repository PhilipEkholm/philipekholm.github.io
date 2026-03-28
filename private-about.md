---
layout: page
title: Om mig
permalink: /private/about
section: private
---

<div class="about-layout">
  <div class="about-photo">
    <img src="{{ '/assets/private/kimjphoto_27689.jpg' | relative_url }}" alt="Philip Ekholm" />
  </div>
  <div class="about-text">
{% assign birth_year = 1996 %}
<!-- Accurate enough, my b-day is 30th of Dec, so 363 days a year it'll correctly display my age-->
{% assign age = 'now' | date: '%Y' | minus: birth_year | minus: 1 %}

<h2>Hej!</h2>

<p>Jag heter Philip Ekholm. Jag och är {{ age }} år gammal och bor i Malmö och jobbar som IT-konsult. På fritiden gillar jag att resa, träna CrossFit och Hyrox. Jag dansar också Salsa och Bachata.</p>

<p>Den här delen av hemsidan är mer personlig — här delar jag med mig av foton, resor och annat som inte nödvändigtvis har med jobb att göra.</p>

<h2>Intressen</h2>

<p>Roadtrips, fotografi, CrossFit, Hyrox, Salsa, Bachata.</p>

  </div>
</div>
