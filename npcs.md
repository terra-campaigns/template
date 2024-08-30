---
layout: default
title: People
nav_order: 75

---

# People


{% for npc in site.npcs %}
  <h2>
    <a href="{{ npc.url }}">
      {{ npc.title }} - {{ npc.title }}
    </a>
  </h2>
  <p>{{ npc.content | markdownify }}</p>
{% endfor %}


But also I can link one single [Link](../directory/_npcs/exampleA.md)

