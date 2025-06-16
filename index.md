---
layout: home
author_profile: true
lang: fr
---

{% assign current_lang = page.lang | default: site.lang | default: 'fr' %}
{% assign t = site.data.lang[current_lang] %}

{{ t.title }}

{{ t.paragraph1 }}

{{ t.paragraph2 }}

<p>
  <a href="/?lang=fr">🇫🇷 Français</a> |
  <a href="/?lang=en">🇬🇧 English</a>
</p>
