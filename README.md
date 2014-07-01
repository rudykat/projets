projets
=======
Ceci est un répositoire créé dans le but de pouvoir montrer divers projets à quiconque le voudra facilement. Les projets présentés ne sont pas très développés ni spécialement intéressants si vous êtes dans une optique de développement et que vous cherchez des librairies ou même une source d'inspiration...

--- Step sampler ---

Il s'agit du projet le plus abouti et "utile" : c'est un sampler créé avec PureData (pd-extended plus précisément) très vaguement inspiré des Korg Electribes ES-1 ; ayant 4 voix, contrôlées par 4 séquenceurs à 16 pas (la longueur est ajustable, on peut si l'on veut en avoir moins, pour faire des motifs polyrythmiques par ex., ou alors il possible de faire comme si il en a jusqu'à 32 pour lire de longs échantillons). Les sequenceurs peuvent lire les pas a une vitesse égale à l'opération tempo général / le nombre entrant dans l'atome "metro-div".

Les sampleurs peuvent ralentir ou accélérer la vitesse de lecture des échantillons, chaque voix à un delay avec LFO + une reverb. Des sliders permettent de choisir approximativement les points de départ et fin des "têtes de lecture" d'un échantillon. Il y a aussi un slider de volume et un objet clip~ permettant de limiter de façon très basique les signaux.

Il y a aussi 4 séquenceurs à 8 pas maximum inspirés de leurs équivalents analogiques pouvant envoyer des valeurs numériques à diverses fonctions : la vitesse de lecture, et les points de départ et de fin de la "tête de lecture" (valeurs entre 0 & 100).

Il y a deux problèmes par contre : tout d'abord ce projet a été fait pour mon amusement personnel et donc l'interface graphique n'a pas été optimisée pour sa beauté ainsi que son ergonomie, et puis il y a un bug qui fait que l'on doit bouger les sliders modifiant les points de départ et fin si l'on veut lire correctement un échantillon. J'espère avoir le temps et la motivation pour corriger ces problèmes et rajouter d'autres fonctions (4 voix supplémentaires, peut être un mapping MIDI avec le Nanokontrol 2 de Korg)

--- Creature 3000 ---

Il s'agit d'un ersatz de jeu (sans côté ludique) fait avec Processing pour valider un semestre lors de mes études, dans le but de montrer que je pouvais appliquer des concepts vu en cours (POO, tableaux dynamiques) dans une situation plus ou moins pratique.  
