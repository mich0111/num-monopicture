# num-monopicture
Widget pour info numériques à image unique avec mise en exergue de la valeur.

Widget permettant l’affichage d’info numérique avec image unique optionnelle et valeur numérique en surimpression.

Le fond et l'image superposée sont paramétrables.

Si l'option est retenue, le bandeau de bas de vignette évolue en fonction de la valeur et des paramètres saisis.
Par défaut le bandeau est monochrome, si des valeurs min et max sont fournies, alors il y aura 3 couleurs différentes paramétrables en fonction de la valeur de la commande. Pour changer les paramétres par défaut de ces bandeaux et couleurs de texte des bandeaux.
Vous devrez utiliser les standards HTML de nommage de couleur.

L’installation préalable du widget Multi-action-Defaut de @JAG est un prérequis.

Les images de fond, standards ou optionnels, devront se trouver dans le répertoire “data/customTemplates/dashboard/cmd.action.other.Multi-action-Defaut/fond” .
Les images superposées devront se trouver dans le répertoire “data/customTemplates/dashboard/cmd.action.other.Multi-action-Defaut/” auquel il convient d’ajouter le nom du dossier spécifique.
Si les images requises ne s’y trouvent pas, vous devrez les transférer par Jeexplorer.

Ce widget bascule automatiquement du thème sombre au clair et adapte le fond du widget en conséquence.

Les images à afficher devront être au format png.

Voici les paramètres à prendre en compte pour l’utilisation de ce widget.

    - min : (optionnel), valeur de la borne minimale, bandeau min.
    - max : (optionnel) > min, valeur de la borne maximale, bandeau max.
    - icon : (optionnel), nom de l’image, pour “image.png”, passer “image”).
    - folder : (optionnel), nom du dossier de l’image (vent, eau, …).
    - colbanmin : (optionnel), couleur du bandeau si la valeur de la commande <= min - Par défaut ="blue".
    - colbanmax : (optionnel), couleur du bandeau si la valeur de la commande >= max - Par défaut = "red".
    - colbanin : (optionnel), couleur du bandeau si la valeur de la commande entre min et max - Par défaut = "gray".
    - coltxtbnmin : (optionnel), couleur du texte du bandeau si la valeur de la commande <= min - Par défaut = "white".
    - coltxtbnmax : (optionnel), couleur du texte du bandeau si la valeur de la commande >= max - Par défaut = "white".
    - coltxtbnin : (optionnel), couleur du texte du bandeau si la valeur de la commande entre min et max - Par défaut = "white".
    - coltxtval : (optionnel), couleur du texte de la valeur de la commande - Par défaut = "black".
    - blink : (optionnel), si = "yes", clignotement du bandeau et de la valeur si celle-ci est hors bornes - Par défaut = "no".
    - theme : (optionnel), nom du thème de fond à afficher. Les fichiers de fond devront alors s’appeler fo_bkg_nom_dark.png et fo_bkg_nom_light.png. Si le paramètre est absent, les thèmes par défaut seront affichés.
    

Résultat à l'affichage:

![monopicture](https://user-images.githubusercontent.com/54777712/72202353-ae0ed800-345e-11ea-8fd1-0ccdbeda48e3.gif)
