---
layout: default
---

This is a small site maintained by Max Heinritz to keep track of the freight concepts that he's learned over the years. Please email maxheinritz@gmail.com if you see something amiss.

<ul>
  {% for term in site.terms %}
    <li>
      <a href="{{ term.url }}">{{ term.title }}</a> - {{ term.preview }}
    </li>
  {% endfor %}
</ul>

Hopefully more soon!