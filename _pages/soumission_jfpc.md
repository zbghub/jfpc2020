---
layout: page_jfpc
show_meta: false
permalink: jfpc/soumission
title: Soumission
published: true
---

Une soumission peut être :
  - un article long : 10 pages,
  - un article court : 4 pages<sup>[1](#n1){:.fnref #ref1}</sup>,
  - un article très court condensant un article déjà publié : 2 pages<sup>[2](#n2){:.fnref #ref2}</sup>.

L'archive des « Consignes aux auteurs » contient la classe LaTeX jfpc ainsi qu'un document d'exemple détaillant toutes les recommandations.

[1](#ref1){:#n1}. Les articles courts peuvent, par exemple, présenter des travaux préliminaires de jeunes chercheurs, un panorama des travaux en cours au sein d'un projet de recherche ou d'un laboratoire, une application résolue avec la programmation par contraintes, ou encore un logiciel de programmation par contraintes.
{:.sidenote}

[2](#ref2){:#n2}. Pour éviter que les meilleurs travaux de la communauté francophone ne soient uniquement présentés dans les congrès internationaux, il est en outre possible de soumettre des condensés d'articles soumis ou publiés. Il peut s'agir d'articles récemment publiés dans les grandes conférences internationales (telles que IJCAI, ECAI, AAAI, CP, CPAIOR, SAT, UAI...) ou des revues. L'article devra avoir été publié après les dernières JFPC (juin 2018), mais avant les prochaines (juin 2019). Le condensé sur 2 pages sera en français et mentionnera explicitement l'article original. Ce type de soumission avec un processus de relecture plus succinct permettra ainsi à leurs auteurs de présenter à notre communauté certains de leurs derniers travaux.
{:.sidenote}


# Dates importantes


{% for date in site.data.dates_jfpc -%}
  - {{ date.title }} {% if date.info -%} <span style="font-size:0.75em;">{{ date.info }} </span>{% endif -%} : {{ date.date }}
{% endfor %}