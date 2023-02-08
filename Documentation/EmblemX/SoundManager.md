SoundManager & MusicManager

L'objectif est de créer un prefab générique que l'on pourra utiliser dans chaque scène depuis n'importe où pour pouvoir jouer un SFX/Musique.

Exemple d'usage:
![[DocSoundManager.PNG]]


Tous les sfx et toutes les musiques sont centralisées dans un *AOT Dictionary*

Les dictionnaires sont des structures de données qui font correspondre une clef à une valeur.

Note  sur *Don'tDestroy on load*
Ces managers ont vocation à survivre à un changement de scène, pour cela on les range dans **Don'tDestroy on load**
