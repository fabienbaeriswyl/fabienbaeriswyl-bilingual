---
layout: home
author_profile: true
---

{% assign lang_param = 'fr' %}
{% if page.url contains 'lang=en' %}
  {% assign lang_param = 'en' %}
{% endif %}
{% assign t = site.data.lang[lang_param] %}

{{ t.title }}

{{ t.paragraph1 }}

{{ t.paragraph2 }}

<p>
  <a href="/?lang=fr">🇫🇷 Français</a> |
  <a href="/?lang=en">🇬🇧 English</a>
</p>
