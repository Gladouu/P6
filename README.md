
# [Détectez des faux billets](https://openclassrooms.com/fr/paths/65/projects/147/assignment) 


#### Compétences évaluées : 

  - Modéliser grâce à la régression logistique
  - Utiliser un algorithme de clustering de type Kmeans
  - Interpréter une ACP
  - Réaliser une ACP

<br> 

## Notebook : 

📗 ***[Analyse des données](https://github.com/Gladouu/P6/blob/main/P6_01_analysis.ipynb)***

<br>

## Scénario : 

Votre société de consulting informatique vous propose une nouvelle mission au ministère de l'Intérieur, dans le cadre de la lutte contre la criminalité organisée, à l'Office central pour la répression du faux monnayage. Votre mission si vous l'acceptez : créer un algorithme de détection de faux billets.
Vous vous voyez déjà en grand justicier combattant sans relâche la criminalité organisée en pianotant à mains de maître votre ordinateur, pour façonner ce fabuleux algorithme  qui traquera la moindre fraude et permettra de mettre à jour les réseaux secrets de faux-monnayeurs ! La classe, non ?
... Bon, si on retombait les pieds sur terre? Travailler pour la police judiciaire, c'est bien, mais vous allez devoir faire appel à vos connaissances en statistiques, alors on y va !
 
<br> 

## Les données : 

La PJ vous transmet un [jeu de données](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/parcours-data-analyst/notes.csv) contenant les caractéristiques géométriques de billets de banque. Pour chacun d'eux, nous connaissons :
  - la longueur du billet (en mm) ;
  - la hauteur du billet (mesurée sur le côté gauche, en mm) ;
  - La hauteur du billet (mesurée sur le côté droit, en mm) ;
  - la marge entre le bord supérieur du billet et l'image de celui-ci (en mm) ;
  - la marge entre le bord inférieur du billet et l'image de celui-ci (en mm) ;
  - la diagonale du billet (en mm).


<br>

## Livrables : 

Le livrable attendu est un fichier .zip contenant :

  - le code Python ou R de l’analyse complète (un ou plusieurs fichiers) ;
  - les graphiques générés par le code, en format image.

<br>

## Overview : 

- Pairplot 

![03  Pairplot](https://user-images.githubusercontent.com/45063193/138316064-149d06ae-9e9c-4ce5-80a2-6a6cb4e61010.jpg)

- Triangle des corrélations

![04  Triangle de corrélation](https://user-images.githubusercontent.com/45063193/138316240-cfe06635-9add-4625-a4ed-247754b1b634.jpg)

- Silhouette Plot 

![09  Silhouette plot Analysis with k = 2](https://user-images.githubusercontent.com/45063193/138316447-a95dc1fb-9173-4d87-8f3e-faa2680d8863.jpg)





  
