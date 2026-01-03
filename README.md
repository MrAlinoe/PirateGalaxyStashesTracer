# PirateGalaxy StashesTracer
[Ouvrir l'application Web](https://mralinoe.github.io/PirateGalaxyStashesTracer/)

Cet outil a été conçu dans le but de faciliter la chasse aux trésors de Noël dans le jeu [Pirate Galaxy]([https://pages.github.com/](https://pirategalaxy.com)), il est inutile si vous n'y jouez pas...
### Comment ça marche?
1) Vous entrez les coordonnées du point où vous êtes ainsi que la distance, plusieurs méthodes sont disponibles, cliquer sur la carte *(coordonnées uniquement)*, utiliser le pavé numérique fourni ou votre clavier,
   - **Clavier:** "Enter" passe à la case suivante, si il est utilisé sur la dernière des 3 cases il ajoute le point à la mémoire, Backspace/"-" efface les chiffres dans la case, si la case sélectionnée est vide, la sélection revient à la case précédente,
   - **Pavé numérique:** Le bouton rouge remplit le rôle de Backspace/"-", le bouton vert celui de "Enter",
   - Le système ne validera pas le point si les coordonnées ne sont pas entre 0 et 100, ce point n'étant pas possible dans le jeu,
2) Le point ajouté est rendu sur la carte sous la forme d'un cercles, répéter l'opération ajoutera jusqu'à 3 cercles, les points d'intersection entre ces cercles vont être des endroits probables où se trouve la cache,
   - Plus les points de repères sont éloignée plus il sera facile de trouver la position de la cache,
3) Une fois la cache trouvée et ouverte et votre déception d'avoir trouvé un doublon de plan au lieu du dernier plan qu'il vous manque passée, appuyez sur le bouton "Cancel" pour effacer les points,

### Paramètres supplémentaires:
1) Le drone actif, chaque drone garde jusqu'à 3 points en mémoire,
   - Si vous équipez plusieurs drones (6 au maximum), chaque drone va pointer vers une cache différente,
2) Le choix de planète: Kalabesh, Aurora, Technatoria, Molikar,
   - Kalabesh se fait en Phoenix S, avec des modules bas niveau, aucun Mantis hostile n'est présent hors mission,
   - Aurora est assez simple à naviguer, c'est la planète où beaucoup de joueurs se rassemblent pour la chasse aux bonhomes de neiges,
   - Technatoria, bah euh... J'ai complètement oublié pourquoi elle était là,
   - Molikar, vous voulez utiliser un Hunter, un Slate ou un Sable pour chercher vos caches rapidement? Bah Mizar est là pour ça,

### Notes:
*Des outils similaires existent utilisant la trilatération ou encore cette même méthode à savoir les cercles, le but ici est de fournir une interface web compatible pour les navigateurs mobiles.*
Les ressources comme la cartes ansi que certaines images venant du jeu ont été récupérées ici: [HGG/Prelude](https://prelude-myzen.co.uk/)
Ce site propose d'ailleur un outil pour les caches par trilatération pour toutes les planètes du jeu...

### Licence:
Cette application est surtout sur Github parce que Github Pages permet de rendre l'application accessible sans frais
La licence est disponible dans les fichiers

Notez que les images ne son pas de moi à l'exception du logo, vous pouvez donc les récupérer, c'est pas mon problème.
Ces dernières appartiennent pour la plupart à SplitScreens Games, veuillez noter que des droits d'auteurs peuvent s'appliquer.

### Notes relatives au dévelopement:
A l'origine, la page web devait etre une page unique embarquant HTML/CSS/JS ainsi que les images (en les embarquand en base64 dans le fichier HTML) dans un fichier unique pouvant etre téléchargé sur n'importe quel appareil ou etre intégré à une application externe permettant d'introduire les données sans quitter la fenètre du jeu... Le soucis est que Notepad++, utilisé pour écrire le code, subissait d'énormes pertes de performances quand les ressources étaient intégrées au fichier rendant tout dévelopement horrible et que l'application avait une compatibilité inconsistante...

Voila, vous savez désormais pourquoi le code est aussi chaotique et devrait être ré-écrit.

*A cette date 01/06/2024, l'application respecte les règles du jeu, ce programme n'a aucune interaction avec le jeu en lui-même...*
