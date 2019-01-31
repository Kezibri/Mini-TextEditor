# [M1 Miage - ACO] Mini-éditeur

Ce projet s'inscrit dans le cadre des travaux pratiques de l'UE ACO. Il s'agit de développer un mini-éditeur 
de texte en Java, offrant des fonctionnalités typiques d'édition de texte.

Le but de ce projet est de réaliser un mini-éditeur en Java sous trois versions:
- Commandes de base : copier, coller, couper, sélectionner...
- Enregistrer et Rejouer des macros
- Undo et Redo

Les versions doivent être imbriquées les unes dans les autres sans casser le code entre versions.
Cela permet de travailler avec différents design patterns.
Les trois versions comportent:
 - La version 1 : Comporte uniquement les actions d'édition de base : sélectionner, copier, couper, coller, supprimer ...
 - La version 2 : Permet d'enregistrer des actions de l'utilisateur et de les rejouer.
 - La version 3 : Permet de réaliser le défaire/refaire des actions de l'utilisateur.
Les versions doivent être imbriquées les unes dans les autres tout en gardant le bon fonctionnement des versions qui précédent.

Pour mener à bien ce projet, plusieurs outils ont été imposés : MagicDraw pour rélaiser la conception des différentes versions en UML, 
Java comme langage de programmation, L'IDE Eclipse, et enfin Junit pour implanter des tests unitaires des différentes fonctionalités de l'application.
