---
layout: default
title: Publications
description: "Journal articles, conference papers, and graduate thesis by Seongbin An."
---

# Publications

Publications are grouped by type and listed from newest to oldest within each group. My name is shown in **bold**. A full, externally indexed record is available through Google Scholar in the footer.

## Journal articles

<ol class="bibliography">
{% assign entries = site.data.publications | where: 'category', 'journal' %}
{% for pub in entries %}
{% include citation.html pub=pub %}
{% endfor %}
</ol>

{% assign next_number = entries | size | plus: 1 %}

## International conferences

<ol class="bibliography" start="{{ next_number }}">
{% assign entries = site.data.publications | where: 'category', 'international' %}
{% for pub in entries %}
{% include citation.html pub=pub %}
{% endfor %}
</ol>

{% assign group_size = entries | size %}
{% assign next_number = next_number | plus: group_size %}

## Domestic conferences

<ol class="bibliography" start="{{ next_number }}" lang="ko">
{% assign entries = site.data.publications | where: 'category', 'domestic' %}
{% for pub in entries %}
{% include citation.html pub=pub %}
{% endfor %}
</ol>

{% assign group_size = entries | size %}
{% assign next_number = next_number | plus: group_size %}

## Graduate thesis

<ol class="bibliography" start="{{ next_number }}">
{% assign entries = site.data.publications | where: 'category', 'thesis' %}
{% for pub in entries %}
{% include citation.html pub=pub %}
{% endfor %}
</ol>
