# seaLevelProjet.github.io

# Données
Notre visualisation a pour but de montrer l'évolution du niveau de la mer.
Nous avons récupéré des données du niveau de la mer de 1880 à 2015 en considérant que le niveau de la mer vaut 0 en 1880.
Nous avons aussi des données de température de 1880 à 2015.

De plus, en se basant sur ces données, nous avons fait des prédictions (sur R) du niveau de la mer et de la température jusqu'en 2400. Nous avons réalisé trois prédictions : une optimiste, une pessimiste et une intermédiaire. Pour cela nous avons utilisé un modèle exponentiel en faisant varié le paramètre avec 3 valeurs différentes.

Les jeux de données ont été récupérés à cette adresse : https://datahub.io/core/sea-level-rise#resource-sea-level-rise_zip



# Objectifs
Notre objectif est de montrer la corrélation entre l'augmentation de la température et l'augmentation du niveau de la mer mais aussi de montrer les conséquences possibles de ces augmentations.

# Réalisation
La visualisation comporte deux graphiques :

- Un "triangle" (en haut à gauche) : Ce triangle représente une côte qui se fait peu à peu submerger par l'eau. Ce graphique permet de voir la montée des eaux au cours du temps à l'aide du slider temporel placé au dessus de la visualisation.
Le long de la pente sont placés plusieurs grandes villes dans le but d'observer les villes qui seront submergées si le phénomène continue sur cette lancée. En passant sur une ville on peut obtenir des informations supplémentaires comme l'altitude, la population, ...

- Un streamgraph : Ce streamgraph permet de visualiser à la fois l'évolution de l'augmentation de la température moyenne sur la surface du globe au cours du temps mais aussi l'évolution du niveau de la mer sur Terre grâce à l'épaisseur du streamgraph. On voit une corrélation entre niveau de la mer et température puisque au cours des années le niveau de la mer et la température augmente en même temps.

# Améliorations

Suite à la présentation, nous avons modifié des éléments de la visualisation. Nous avons réalisé deux versions :

- Version 2 : Version qui ne comporte pas les prédictions de température jusqu'en 2400. Il nous a été demandé d'ajouté les prédictions de températures jusqu'en 2400 sur le streamgraph, nous pensons qu'en ajoutant cela la visualisation n'est plus esthétique. C'est la version que nous préférons.

- Version 3 : Version qui comporte les prédictions de température sur le streamgraph.

Un élément à été ajouté à la visualisation :

- Une jauge verticale : Sur les versions 2 et 3 (qui font suite à la présentation), nous avons placé une jauge verticale à gauche des graphiques pour permettre d'observer la montée des eaux de manière linéaire. Cela permet de bien voir l'explosion du phénomène qui n'était pas visible avec l'échelle logarithmique utilisée pour le graphique. Nous avons fait le choix de laisser l'échelle logarithmique qui permet de voir les petites variations du niveau de la mer qui ne sont pas visibles avec l'échelle linéaire.

Nous avons aussi modifié l'affichage des villes le long de la pente.

# Sources
Pour réaliser ce projet, nous nous sommes inspirés des exemples de Mike Bostock ainsi que de cette visualisation : https://bl.ocks.org/lsbardel/d686414f38742cb60c3bf3f21b79b9df (pour faire les vagues).





# Data
Our visualization is intended to show the evolution of sea level. We have retrieved sea level data from 1880 to 2015 based on the assumption that sea level was 0 in 1880. We also have temperature data from 1880 to 2015.

In addition, based on these data, we made predictions (on R) of sea level and temperature up to 2400. We have made three predictions: an optimist, a pessimist and an intermediary. For this purpose we used an exponential model by varying the parameter with 3 different values.

The data sets were retrieved from this address: https://datahub.io/core/sea-level-rise#resource-sea-level-rise_zip

# Objectives of the project
Our objective is to show the correlation between temperature increase and sea level rise but also to show the possible consequences of these increases.


# Realization
The visualization consists of two graphs:

- A "triangle" (top left): This triangle represents a coast that is gradually being submerged by water. This graph allows to see the rise of the water over time using the temporal slider placed above the visualization.
Along the slope are placed several large cities in order to observe the cities that will be submerged if the phenomenon continues in this direction. By passing over a city you can obtain additional information such as altitude, population,...

- A streamgraph: This streamgraph makes it possible to visualize both the evolution of the increase in the average temperature on the surface of the globe over time but also the evolution of sea level on Earth thanks to the thickness of the streamgraph. There is a correlation between sea level and temperature since over the years sea level and temperature increase at the same time.

# Improvements

Following the presentation, we modified elements of the visualization. We have made two versions:

- Version 2: Version that does not include temperature predictions up to 2400, we have been asked to add temperature predictions up to 2400 on the streamgraph, we think that by adding this the visualization is no longer aesthetic. This is the version we prefer.

- Version 3: Version that includes temperature predictions on the streamgraph.

An element has been added to the visualization:

- A vertical gauge: On versions 2 and 3 (following the presentation), we placed a vertical gauge to the left of the graphs to allow a linear view of the rising water. This makes it possible to clearly see the explosion of the phenomenon that was not visible with the logarithmic scale used for the graph. We have chosen to leave the logarithmic scale which allows us to see small variations in sea level that are not visible with the linear scale.

We also modified the display of cities along the slope.

# Sources
To carry out this project, we drew inspiration from Mike Bostock's examples and this visualization: https://bl.ocks.org/lsbardel/d686414f38742cb60c3bf3f21b79b9df (to make the waves).

