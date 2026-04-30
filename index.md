---
title: Marisa Pickett
layout: nav-profile
date: 2024-12-02
---


# Marisa Pickett

I'm a PhD candidate in the Department of History at the University of New Mexico. My focus is  modern comparative European history. My research focuses on Black European culture, community, politics and creativity within which the transatlantic exchange of Black ideas and art between Europe and the USA. I look to understand the experiences of those 'othered' by white society, living within their own created communities and crafting identities that encompass their experiences.

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