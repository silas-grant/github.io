---
title: Silas Grant
layout: nav-profile
date: 2024-12-02
---


# Your Name

I am a scholar of technoscience, empire, and gender & sexuality. My research is broadly concerned with environmental justice and the politics of knowledge in the Southwestern United States. I am currently Visiting Assistant Professor in the Department of American Studies and affiliate faculty in the Department of Geography & Environmental Studies at the University of New Mexico. I am based on Tiwa lands in Albuquerque, New Mexico. 


{% include images/figure.html
  image-path="assets/images/silasgrant-_DSC3820.jpg"
  class="center"
  width="60%"
  caption="Silas Grant"
  alt-text=
%}



---

The cards below are generated automatically from your other pages. Each page that has `homepage: true` in its front matter will appear here as a card. The card's title, summary text, and thumbnail image all come from that page's front matter:

```yaml
homepage: TRUE
summary: A sentence or two describing this page — appears on the card.
thumbnail: assets/images/your-image.jpg
position: 1   # controls the order cards appear (lower numbers first)
```

To add a new card, create a new page and add those fields. To remove a card, delete `homepage: TRUE` from that page's front matter. To reorder cards, adjust the `position` values.

{% assign essays = site.pages | where: "homepage", true %}
{% include nav/card-stack.html cards = essays %}