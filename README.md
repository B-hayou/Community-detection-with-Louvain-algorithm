# Community-detection-with-Louvain-algorithm

Le but de ce projet est de déterminer le meilleur partitionnement possible des communautés au sein d'un réseau.

Nous mettons en œuvre des algorithmes de détection de communauté en utilisant les données de **Facebook**. 

Pour ce faire, nous entraînons la méthode de **Louvain**, qui est un algorithme **glouton** et qui consiste à trouver des groupes de nœuds très liés entre eux par la maximisation de la modularité définie dans le rapport:

* Les données comprenaient les utilisateurs en tant que nœuds et leurs relations entre amis en tant que bords.
* Test basé sur des graphes aléatoires, afin de comparer la performance de notre méthode. 


## Obtenir le code 

Vous pouvez cloner le dépôt sur votre machine locale et y accéder avec les commandes suivantes : 

```sh 
$ git clone https://github.com/B-hayou/Community-detection-with-Louvain-algorithm.git
```
```
$ cd Community-detection-with-Louvain-algorithm
```
## Documentation
 
La documentation du jeu de données est disponible [ici](https://snap.stanford.edu/data/ego-Facebook.html?fbclid=IwAR1HI3gBO5eqh7FfR3ZMBTADCMYftpHGoI7MN1kfZFDYwhEBNqvMqOei88c) pour le réseau graphique. 

## Structure 
La structure de notre projet est la suivante : 

* L'algorithme principal est implémenté dans le dossier `./LOUVAIN ALGORITHM`. Un notebook Jupyter .ipynb contient le code pour entraîner le modèle et analyser les résultats. 

* La présentation du rapport est conservée dans le dossier ./rapport. 

## Membres

- Belgaid Jihène, jihène.belgaid@etu.umontpellier.fr
- Chaoui Wiam, wiam.chaoui@etu.umontpellier.fr
- Goujili Nouhaila, nouhaila.goujili@etu.umontpellier.fr
- Hayou Bouthayna, bouthayna.hayou@etu.umontpellier.fr

## Sources



