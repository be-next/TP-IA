# Datasets

## NBA Players
  - players_stats.csv : https://www.kaggle.com/datasets/drgilermo/nba-players-stats-20142015

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
