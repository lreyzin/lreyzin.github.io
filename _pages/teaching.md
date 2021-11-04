---
layout: page
permalink: /teaching/
title: teaching
description:
years: [Spring 2022, Fall 2021, Spring 2021, Fall 2020, Spring 2020, Fall 2019, Spring 2019, Winter 2019, Fall 2018, Spring 2018, Fall 2017, Spring 2017, Fall 2016, Spring 2016, Fall 2015, Spring 2015, Fall 2014, Spring 2014, Fall 2013, Spring 2013, Fall 2012, Spring 2012]
nav: true
heading: teaching
---

Below are listed all the courses that I have taught as the primary instructor (or co-instructor), with
links to their respective websites.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f classes -q @*[year={{y}}]* %}
{% endfor %}

</div>
