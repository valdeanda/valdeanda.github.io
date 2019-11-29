---
title: "Valerie de Anda- Publications"
layout: gridlay
excerpt: "Valerie de Anda -- Publications."
sitemap: false
permalink: /publications/
---

Jump at the bottom of the page to see a [full list of publications](#full-list), our [Preprints](#preprints), and [Book chapters](#books-and-book-chapters).

## Highlights

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="50%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p>{{ publi.authors }}. {{ publi.year }}. {{ publi.title }}. <em><a href="{{ publi.link.url }}">{{ publi.link.display }}. {{ publi.doi }}</a></em></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Full List

{% for publi in site.data.publist %}

  {{ publi.authors }}. <strong>{{ publi.year }}</strong>. {{ publi.title }}. <em><a href="{{ publi.link.url }}">{{ publi.link.display }}. {{ publi.doi }}</a></em>

{% endfor %}

## Preprints
{% for publi in site.data.preprintlist %}

  {{ publi.authors }}. <strong>{{ publi.year }}</strong>. {{ publi.title }}. <em>{{ publi.link.display }}</em>

{% endfor %}

## Books and book chapters

{% for publi in site.data.booklist %}

  {{ publi.authors }}. <strong>{{ publi.year }}</strong>. {{ publi.title }}. <em>{{ publi.link.display }}</em>

{% endfor %}
