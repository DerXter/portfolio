---
title: A Few Thousand Translations Go a Long Way! Leveraging Pre-trained Models for
  African News Translation
date: 2023-02-08T11:05:24+00:00
image: "/images/using-machine-learning-to-enable-the-translation-of-local-african-languages.png"
author: Derguene Mbaye
description: 'MAFAND-MT: Traduction Automatique pour les Langues Africaines'
links:
- label: Papier
  link: https://aclanthology.org/2022.naacl-main.223/
- label: Github
  link: https://github.com/masakhane-io/lafand-mt

---
Les progrès récents dans le pré-entraînement des modèles de langue s'appuient sur des jeux de données à grande échelle pour créer des modèles multilingues. Cependant, **les langues à faibles ressources sont généralement laissées de côté** dans ces ensembles de données. Cela s'explique principalement par le fait que de nombreuses langues largement parlées ne sont pas bien représentées sur le Web et sont donc exclues des recherches à large échelle utilisées pour créer les ensembles de données. En outre, **les utilisateurs en aval de ces modèles sont limités à la sélection des langues choisies à l'origine pour le pré-entraînement**.

Ce travail étudie **comment exploiter de manière optimale les modèles pré-entraînés existants afin de créer des systèmes de traduction à faibles ressources pour 16 langues africaines.** Nous nous concentrons sur deux questions :

1. Comment les modèles pré-entraînés peuvent-ils être utilisés pour des langues non incluses dans le pré-entraînement initial ?
2. Comment les modèles de traduction résultants peuvent-ils être transférés efficacement à de nouveaux domaines ?

Pour répondre à ces questions, **nous avons créé un nouveau corpus de nouvelles africaines couvrant 16 langues, dont huit ne font partie d'aucun ensemble de données d'évaluation existant**. Nous avons démontré que **la stratégie la plus efficace pour le transfert vers d'autres langues et d'autres domaines consiste à affiner de grands modèles pré-entraînés sur de petites quantités de données de traduction de haute qualité**.