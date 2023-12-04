# Dataset



## NBA Players
  - players_stats.csv : https://www.kaggle.com/datasets/drgilermo/nba-players-stats-20142015

Le dataset "NBA Players Stats - 2014-2015" contient des données de la saison 2014-2015 pour 182 joueurs de basketball de la NBA.

<details close>
<summary>Il comprend 25 variables, qui sont les suivantes :</summary>

  - Player: Nom du joueur.
  - Position: Position du joueur (PG = meneur, SG = arrière, PF = ailier fort, SF = ailier, C = pivot).
  - Age: Âge du joueur en années.
  - Team: Nom de l'équipe.
  - Games: Nombre de matchs joués (sur un total de 82).
  - Starts: Matchs commencés.
  - Mins: Minutes jouées.
  - MinPerGame: Minutes par match.
  - FGMade: Tirs réussis.
  - FGAttempt: Tirs tentés.
  - FGPct: Pourcentage de réussite aux tirs.
  - FG3Made: Tirs à trois points réussis.
  - FG3Attempt: Tirs à trois points tentés.
  - FG3Pct: Pourcentage de réussite aux tirs à trois points.
  - FTMade: Lancers francs réussis.
  - FTAttempt: Lancers francs tentés.
  - FTPct: Pourcentage de réussite aux lancers francs.
  - OffRebound: Rebonds offensifs.
  - DefRebound: Rebonds défensifs.
  - Rebounds: Total de rebonds.
  - Assists: Nombre de passes décisives.
  - Steals: Nombre de interceptions.
  - Blocks: Nombre de contres.
  - Turnovers: Nombre de pertes de balle.
  - Fouls: Nombre de fautes personnelles.
  - Points: Nombre de points marqués​​​​.
</details>

La particularité du dataset "NBA Players Stats - 2014-2015" réside dans sa concentration sur des données statistiques détaillées de joueurs individuels de la NBA pendant la saison régulière 2014-2015. Voici quelques points qui soulignent sa spécificité :

  - Couverture Complète de Joueurs: Le dataset inclut des données sur 182 joueurs de la NBA, offrant une vue d'ensemble complète des performances des joueurs pendant la saison.
  - Diversité des Statistiques: Avec 25 variables distinctes, le dataset fournit une analyse détaillée des performances des joueurs, couvrant non seulement les points marqués mais aussi d'autres aspects importants du jeu comme les rebonds, les passes, les contres, les interceptions, et les fautes.
  - Mesure de la Performance: Les statistiques recueillies permettent une évaluation complète de la performance des joueurs, offrant des insights pour des analyses avancées comme l'évaluation de l'efficacité des joueurs, les comparaisons entre les joueurs, et l'identification des tendances de jeu.
  - Applications Analytiques Variées: Ce dataset peut être utilisé pour une multitude d'applications analytiques, allant de la simple statistique descriptive à des analyses plus complexes comme le machine learning, la prédiction de performances, ou l'analyse de réseaux.
  - Intérêt pour les Fans et Analystes de Basket: Les données de ce genre sont très prisées par les fans de basketball, les entraîneurs, les analystes sportifs, et les chercheurs en analyse sportive, car elles fournissent des insights précieux sur le jeu et les joueurs.

## Image Segmentation

  - segmentation_test.csv : https://archive.ics.uci.edu/dataset/50/image+segmentation

La particularité de ce dataset de segmentation réside dans son approche spécifique pour la classification des pixels. Chaque instance dans ce dataset est une région de 3x3 pixels, tirée de l'une des 7 images extérieures. Ces images ont été segmentées manuellement, ce qui signifie que chaque pixel a été classé par un humain, offrant ainsi un ensemble de données très précis pour l'entraînement de modèles de machine learning, en particulier pour les tâches de segmentation d'image.

Concernant le calcul des caractéristiques, chaque instance (région de 3x3 pixels) contient 19 caractéristiques. Ces caractéristiques sont généralement calculées en fonction de divers attributs des pixels au sein de la région. Les caractéristiques dans ce contexte de segmentation d'image incluent des mesures du type :

  - Intensité de couleur: Mesure de la luminosité ou de la couleur des pixels.
  - Texture: Analyse des motifs ou de la structure de surface des pixels.
  - Contraste: Différence d'intensité de couleur entre un pixel et ses voisins.
  - Orientation: Direction prédominante des éléments de texture dans la région.
  - Bordures: Présence et caractéristiques des bordures dans la région.


Ces caractéristiques sont utilisées pour entraîner des modèles de machine learning à reconnaître et à classifier les différents segments d'une image, ce qui est l'objectif de nombreuses applications, telles que la reconnaissance d'objets, la cartographie par satellite, et les systèmes de vision par ordinateur.
