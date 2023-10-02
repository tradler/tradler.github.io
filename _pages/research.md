---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Job market paper
***Child Disability, Family Labor Supply, and the Value of the SSI Program***

Abstract being revised

## Work in progress
***In Sickness and In Health: Intrahousehold Behaviors and Disability Insurance***

Abstract or draft coming soon

***Medical Schools, Physician Maldistribution, and Mortality*** (with Thomas Helgerman)

Abstract coming soon

***Parental Resources and Major Choice*** (with Zsigmond Palvolgyi and Nikhil Rao)

Abstract coming soon

## Pre-Dissertation Work
***Using Payroll Processor Microdata to Measure Aggregate Labor Market Activity*** with Tomaz Cajner, Leland Crane, Ryan Decker, Adrian Hamins-Puertolas and Christopher Kurz

***Racial Gaps in Labor Market Outcomes in the Last Four Decades and over the Business Cycle*** with Tomaz Cajner, David Ratner and Ivan Vidangos


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
