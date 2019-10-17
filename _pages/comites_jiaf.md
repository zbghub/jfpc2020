---
layout: page_jiaf
show_meta: false
permalink: jiaf/comites
title: Comités
published: true
---

{% for comite in site.data.comites_jiaf %}
## Comité {{ comite.type }}

### Présidence
{% for membre in comite.presidence -%}
  - [{{ membre.name }}]({{ membre.website }}) ({{ membre.institution }})
{% endfor %}

### Autre Membres
{% for membre in comite.autre -%}
  - [{{ membre.name }}]({{ membre.website }}) ({{ membre.institution }})
{% endfor %}
{% endfor -%}