---
title: Accueil
---

# Bienvenue sur Showdown Culture

Ici, vous trouverez diverses idées, pensées et propositions sur le
Showdown.

J'espère pouvoir contribuer à votre avancée dans cette discipline qui n'a
pas fini de grandir.

Bonne visite
{% if site.posts %}
# Derniers articles

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

{% endif %}
