---
layout: default
---

<h2>Terms</h2>

<ul>
  {% for term in site.terms %}
    <li>
      <a href="{{ term.url }}">
        {{ term.title }} - {{ term.preview }}
      </a>
    </li>
  {% endfor %}
</ul>

Hopefully more soon!