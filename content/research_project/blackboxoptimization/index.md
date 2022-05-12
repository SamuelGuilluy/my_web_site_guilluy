---
title: SEME - Semaine Mathématiques en Entreprise
summary: Projet d'optimisation boite noire pour l'IRT Saint-Exupéri.
tags:
  - Optimization
date: '2022-05-02T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
Lien vers le streamlit de présentation du projet : https://share.streamlit.io/samuelguilluy/blackboxseme/main/tableau_streamlit.py

Caractérisation de problèmes d’optimisation définis par des fonction de type « boites noires » . 

En aéronautique, l’optimisation de la conception d’un avion fait intervenir plusieurs sous- problèmes de natures différentes : optimisation de l’aérodynamique, optimisation de la structure, etc. (On parle d’optimisation multidisciplinaire.) Il est bien sûr essentiel de choisir pour chaque sous- problème un algorithme d’optimisation performant.

L’optimisation, au sens mathématique, consiste à minimiser (ou maximiser) la valeur d’une fonction objectif tout en respectant des contraintes, également représentées par des fonctions. Pour certains types de fonctions (par exemple convexes, ou même linéaires) on sait associer à un problème des algorithmes efficaces. Cependant les problèmes d’optimisation rencontrés dans l’industrie n’ont pas toujours des propriétés aussi simples à identifier. Ceci est notamment dû au fait que les valeurs des fonctions ne sont pas calculées grâce à des formules analytiques mais plutôt à l’aide de simulations numériques. On parle de fonctions « boîtes noires ». La question du choix de l’algorithme le plus efficace pour résoudre de tels problèmes n’est pas triviale. Pour faciliter ce choix une approche consiste à identifier des propriétés caractéristiques des problèmes.