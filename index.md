---
layout: page
title: &lsaquo;QM&rsaquo; Developers
tagline: Blog para desenvolvedores
---
{% include JB/setup %}

Bem vindos ao Blog do [QMAGICO](http://www.qmagico.com.br/)

Aqui iremos tratar dos mais diversos assuntos ligados a desenvolvimento e projetos de software além de contar coisas legais sobre o que rola na empresa!

Veja abaixo os últimos t posts:

<ul class="posts">
  {% for post in site.posts limit:5 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

Se quiser contribuir com algum post interessante, simplesmente dê um fork no [projeto no GitHub](https://github.com/qmagico/qmagico.github.io) e faça um pull request!
