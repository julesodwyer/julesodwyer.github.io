---
layout: page
permalink: /research/
title: Research
description: 
years: [2022, 2021, 2020, 2019, 2018, 2017]
nav: true
nav_order: 3
---

## Current book projects

### The Seduction of Space: Cruising French cinema

Given that France provided an intellectual home to the most influential spatial theorists of the post-1968 generation, and the nation’s identity and frame of geopolitical influence are often expressed with recourse to geometric metaphors (e.g., *L’Héxagone*, *Francosphère*), the country offers a propitious national context in which to explore questions of space and place. Yet while spatiality has long constituted a vital analytic for discussions of politics and aesthetics in French culture, this book argues that it is the country’s queer cinematic production that has gone the furthest in expanding this rich area of inquiry in recent years. *The Seduction of Space* surveys the largely underexplored work of a number of queer filmmakers, including Jacques Nolot, Marie-Claude Treilhou, Sébastien Lifshitz, Vincent Dieutre, Alain Guiraudie, and Abdellah Taïa. It brings these filmmakers’ shared interests in the politics of cruising and the gendering of space into conversation with film theory, queer studies, and cultural geography to propose new ways of understanding cinematic space. By considering topics as varied as the latent eroticism of the porn theater, race and the eroticization of the *banlieue*, and the ecocritical valence of rural cruising, through to the geopolitics of sexuality in an expanded Francophone frame, this study foregrounds the crucial role that spatiality plays in shaping the parameters of France’s political imaginary and its queer visual cultures. An exercise in reading queer cinematic space, *The Seduction of Space* offers conceptual interventions that resonate far beyond the book’s immediate national context.

### Cinema's Hotels

From the Chateau Marmont to Marienbad, and from the Bates Motel to the Overlook Hotel, the hotels we encounter in the cinema often serve as much more than the mute backdrop against which a film’s action transpires. Rather, hotel spaces actively scaffold the formal, aesthetic, and narrative possibilities of cinema. My current book project considers the parallels between cinema and the hotel--two ‘hyperaesthetic’ spaces that appeal to experiential logics of fantasy, immersion, and aspiration; spaces that mediate our encounters with cultural difference and the world outside. This book reads the hotel as a privileged site for exploring the dynamics and contradictions that structure the modern condition: they are simultaneously public and private, spaces of leisure and labor. Hotel spaces mediate the spatiotemporal registers of the local and the global, historicity and anachronism. Cinema’s Hotels grounds its readings of individual films within broader histories of moving image media. Drawing on a purposefully broad array of cinematic texts—from work by Lila Avilés to Liliana Cavani, and from Andy Warhol to Apichatpong Weeresethakul—I consider both how and why the institution of the hotel holds such a strong purchase in the cinematic imaginary.

---

## Selected Publications

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
