<!--t Nouveau test horodaté t-->

He oui la configuration d'un moteur de blog réserve parfois des surprises. Ici c'est un problème d'horodatage  des fichiers qui m’ennuie...

La seule solution pour savoir si ça marche c'est de tester :)

----------
édit: <br>
Pas avec la solution trouvée...<br>
édit2: <br> feedoo, chez qui j'ai [forké][1] la version de HTMLy, a trouvé les endroits ou étaient cachées les directives de 'TimeZone'. Du coup en les passant toutes à 

> Europe/Paris

 l'horodatage est bon.<br>
les fichiers concernés sont:

 - system/htmly.php
 - system/includes/functions.php
 - system/includes/functions.en.php

  [1]: https://github.com/FredBlain/blog