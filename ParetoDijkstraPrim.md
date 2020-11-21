# ParetoDijkstraPrim
## Description
Projet piscine d'une semaine dans lequel nous devions appliquer les algorithmes de Pareto, Dijkstra et Prim sur plusieurs figures chargées depuis des fichiers.
Chaque figue était composée de plusieurs segments à deux paramètres.
Il était également question d'optimisation du code étant donné qu'un des fichier était assez conséquent. 
## Technologies
* C++
* SVG
## Captures d'écran
Réalisation de l'algorithme de Prim (figure de droite) sur la figue de gauche en fonction du coût rouge, de gauche sur les segments (mono-objectif).<br/>
![alt text](https://github.com/Paulcou/projets-ecole/blob/main/images/Prim.PNG?raw=true "Prim")
Frontière de Pareto établie pour la figure de gauche afin de trouver les solutions les moins coûteuses pour relier tous les points de celle-ci en fonction des deux coûts présents sur les segments (bi-objectif).<br/>
![alt text](https://github.com/Paulcou/projets-ecole/blob/main/images/ParetoRender.PNG?raw=true "Pareto")
Découpage de la figure de gauche en toutes les solutions possibles pour relier tous les points et affichage de la frontière de Pareto en fonction du poids 1 (valeur de gauche sur les segments) et de la somme de tous les Dijkstra réalisés sur la solution (bi-objectif).<br/>
![alt text](https://github.com/Paulcou/projets-ecole/blob/main/images/Dijkstra.PNG?raw=true "Dijkstra")
Une des extensions fût de réaliser la même mission que pour la deuxième image mais avec 3 coûts (tri-objectif).<br/>
![alt text](https://github.com/Paulcou/projets-ecole/blob/main/images/ParetoRender2.PNG?raw=true "Pareto")
