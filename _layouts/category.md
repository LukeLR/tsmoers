---
layout: default
---

# Hier findest du eine Liste aller ProWo-Fotos!
## Banane!

{% for post in site.categories[page.category] %}
    <a href="{{ post.url | absolute_url }}">
      {{ post.title }}
    </a>
{% endfor %}
