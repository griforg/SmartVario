*Note : [aide sur la syntaxe Markdown](https://guides.github.com/features/mastering-markdown/)*

#Proposition d'IHM#

Je propose un affichage type *tête haute* avec en permanence le cap, la vitesse verticale et la vitesse sol. 

##Menu 1 : Mode *Classique*##
Ce mode est destiné a afficher les informations classiques d'un variomètre.

Liste des infos affichées à l'écran :
* Altitude barométrique
* Vitesse sol
* Vitesse verticale
* Finesse sol
* Cap actuel
* *Position GPS?*

Barrette de diodes : vitesse verticale 

Nombre de diodes allumées|Montée : vert|Descente : rouge
:-----------------------:|:-----------:|:---------------:
1|1 à 2 m/s|0-1 m/s
2|2 à 3 m/s|1-2 m/s
3|3 à 4 m/s|2-3 m/s
4|4 à 5 m/s|3-4 m/s
5|>5 m/s|>4 m/s

Si action sur le bouton réglage : *à définir*

##Menu 2 : Mode *Approche*##
Ce mode permet de vérifier que l'on est finesse du terrain

Liste des infos affichées à l'écran :
* Nom du terrain
* Indicateur de direction du terrain
* Finesse nécessaire
* Finesse actuelle *(sans objet si trajectoire à +/- 30° de la direction du terrain?)*
* Marge de hauteur à l'arrivée au-dessus du terrain

Barrette de diodes :
* 6 rouges : terrain hors finesse
* 6 oranges : terrain en finesse mais marge faible : < à 100 m de marge
* 3 vertes : terrain en finesse : entre 100 et 200m de marge
* 6 vertes : terrain en finesse : > 200m de marge

Si action sur le bouton réglage : défilement des terrains enregistrés

##Menu 3 : Mode *Finale*##
Cette vue pourrait proposer une aide à l'atterrissage. Soit une aide à la PTU, plus complexe à programmer, soit, plus simple, une aide la phase finale (trop haut, trop bas par rapport à mon point de visé, ou par rapport aux limites du terrain.

##Menu 4 : Mode *Configuration*##
Ce menu permet de configurer les paramètres de l'appareil :
* Altitude
* Coordonnées des terrains
* Paramètres pour l'affichage des diodes
* etc
