Description du jeu ICRogue : 

Le joueur apparait toujours dans une salle vide au centre de la carte du niveau si aleatoire sinon la salle de coordonnees (1,1).
Son but est d'explorer les differentes sallse du niveau et resoudre le defi de chaque salle(peut etre simplement la visiter ou bien tuer un ennemie) avant d'affronter le 
Boss du niveau situe dans la salle verouillee.
Il passe en suite au niveau suivant (par defaut le premier niveau est fixe et les autres sont des niveau de types 0 et 1 respectivement aleatoires) et recommence l'exploration.

Résolution du jeu ICRogue : Le jeu est résolu si tous les niveaux de jeu sont résolus et donc si toutes les salles de Boss spécifique à chaque niveau sont résolues.

Contrôles :
Flèches directionnelles : déplacement.
La touche W : Ouverture des portes verrouillés (si le personnage a ramassé clé au préalable) et interaction avec le bâton.
La touche X : Permet au personnage de lancer les boules de feu (s’il a ramassé le bâton au préalable).
La touche R : Permet de réinitialiser le jeu (Recommencer le jeu du début).
La touche 0 (Pour l’instant commenté) : Permet de faire passer toutes les portes à l’état ouvert.
La touche L (Pour l’instant commenté) : Permet de faire passer la porte oueste à l’état verrouillé (Une clé d’identifiant 1 permet de l’ouvrir).
La touche T (Pour l’instant commenté) : Permet de tout ouvrir/fermer sauf pour la porte verrouillé.
 
Comment affronter les ennemies :
  1)le Turret:
    Lanche des fleches a intervalle regulier.
  2)le EvolvedTurret:
    Une version evoluee du turret qui se deplace aleatoirement dans la salle en plus des il lance des fleches regulierement.
 Chaque ennemie meurt s'il touche une des boules de feu lancees par le joueur ou si ce derier lui marche dessus.


Obtenir la clé pour ouvrir la porte verrouillé :
Le joueur doit trouver la clé et la récupérer en lui marchant au-dessus ce qui lui permettra d'ouvrir la salle du Boss.

Reccuperation du baton:
Le joueur peut trouver un baton dans l'une des salles du niveau'.
Il peut le reccuperer en s'approchant du baton en suite en cliquant sur la touche W.
Apres la reccuperation, le joueur pour lancer des boules de feu selon son orientation.

Reccuperation avec le coeur :
Le cœur est seulement disponible a partir du niveau 1.
Il est recuperable en lui marchant dessus.
Cette interaction rajoute une vie au joueur s’il n’a pas déjà le nombre maximal de vies 3 , si c’est le cas le joueur ne pourrait pas interagir avec le cœur.

Les fleches:
Les fleches sont les attaques principales des ennemies.
Le joueur doit les eviter tout en essayant de tuer les ennemies.
 

Variation de son niveau de vie (HP) :
Le joueur a par défaut 3 vies (au début du jeu) qui pourront diminuer s’il reçoit une attaque d’un ennemie ou augmenté s’il interagit avec un cœur 
La variation apparait au moyen d’un affichage du nombre des cœurs correspondant à son niveau de vie (3 cœurs pour un niveau de vie égale a 3…).
Le niveau de vie sera réinitialisé lors du passage d’un niveau a un autre.
