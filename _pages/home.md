---
title: "Simulation of European Politics"
layout: splash
permalink: /
date: 2017-04-11 01:48:41 -04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-meu2015.jpg
  _cta_label: "Join Our Network"
  _cta_url: "http://forum.beta-europe.org"
  caption: "Photo credit: [**MEUS 2015**](http://www.meu-strasbourg.org)"
excerpt: "Bringing Europeans Together Association Italia (BETA Italia) is a politically independent and non-profit association to support the organisation of European politics simulations in Italy."

intro_01:
  - title: Our Association
    image_path: /assets/images/beta-logo-600.png
    alt: "Logo of BETA Italia"
    excerpt:
    |
      The Bringing Europeans Together Association Italia (BETA Italia) is a young, politically independent and non-profit association founded in late 2016 by 7 young Europeans in Rome. BETA Italia now counts more than 40 members all across Italy and beyond.
    url: "/contact/"
    btn_label: "People behind BETA Italia"
    btn_class: "btn--primary"
intro_02:
  - title: Our Mission
    image_path: /assets/images/AG tutti.jpg
    alt: "Group Photo BETA Italia"
    excerpt:
    |
      Our mission is to contribute to the development of a European consciousness among the youth and to spread knowledge and awareness about how the European Union works and what does it mean to be a European citizen.
    url: "/about/"
    btn_label: "About Us"
    btn_class: "btn--primary"
intro_03:
  - title: Model European Union Milan
    image_path: /assets/images/23559677_1915987315317244_992415497384255975_n.png
    alt: "MEU 2018"
    excerpt:
    |
      The first international MEU ever organised in Italy will be in Milan from the 23rd to 27th of May! Apply until the 19th of March!
    url: "/2018/02/27/milan-meu-2018-call-for-participants/"
    btn_label: "MEU 2018"
    btn_class: "btn--primary"
intro_04:
  - title: Our Work
    image_path: /assets/images/all-veumeu.jpg
    alt: "VeUMEU Group photo"
    excerpt:
    |
      In order to achieve its goals, BETA Italia organises 3 different MEUs in Italy: Sapientia in Consilium (Rome), VeUMEU (Venice) and MiMEU (Milan). In addition we offer a project called “Insegnare la cittadinanza europea”, whose aim is to discuss the EU with high school students.
    _url: "/calendar/"
    _btn_label: "Conference Calendar"
    _btn_class: "btn--primary"
---

{% include feature_row id="intro_01" type="left" %}

{% include feature_row id="intro_02" type="right" %}

{% include feature_row id="intro_03" type="left" %}

{% include feature_row id="intro_04" type="right" %}

<div class="layout--splash__recent--posts">
<h3 class="archive__subtitle">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent Posts" }}</h3>

{% for post in site.posts limit:3 %}
  {% include archive-single.html %}
{% endfor %}
</div>
