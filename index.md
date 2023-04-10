---
title:  "Verkehrsverein Stein AR"
description: "Test"
---

## Willkommen bei Verkehrsverein Stein AR

Was ist heute los in Stein AR?

### Was läuft heute?

--> Kalender

### Welche Betriebe haben offen?

--> OpenStreetMap und Öffnungszeiten

### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
