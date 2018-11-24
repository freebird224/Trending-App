# Trending-App
Cette application répertorie les dépôts de Github les plus étoilés créés des 30 derniers jours. 

1-Choix des librairies :

Au cours du développement de cette application j'ai travaillé sur Android Studio et le code a été écrit en JAVA.
J'ai utilisé plusieurs librairies pour des besoins :

-	Pour le parsing des données j'ai opté pour la librairie JSON de google. Non seulement c'est la librairie la plus utilisé mais aussi c'est le plus performant.

-	Pour récupérer les données (les dépositoires) à distance, j'ai opté pour la librairie Retrofit.

Actuellement Retrofit est le meilleur choix de librairie pour les appels http en termes de facilité d'utilisation, de performance, d'extensibilité...
Il s'agit d'un client REST de type sécurisé pour Android construit par Square.
En utilisant cet outil, le développeur Android peut se connecter au serveur beaucoup plus facilement.

-	Pour récupérer les avatars, j'ai opté pour la librairie Picasso. Car les images avatars ne sont pas directement stockés dans les dépositoires mais plutôt les adresses url des avatars.

Picasso est une librairie développée par le groupe Square, une communauté de développeurs passionnés d'open-source, qui développe les librairies les plus connues et les plus maintenues de la plateforme Android.
L'utilisation de la librairie Picasso permet :
Le téléchargement de l'image de façon asynchrone depuis une URL
La Gestion du cache d'une image
La réduction de la taille d'une image
L'insertion de l'image dans une ImageView
La transformation d'images complexes avec un minimum d'utilisation de la mémoire.

2- Utilisation de l'application :

1-Télécharger le fichier compressé trending.zip et décompresser.
2-Importer le projet dans Android Studio.
3-Vérifier votre compileSdkVersion dans le fichier gradle. (Personnellement c'était 27). Si c'est pas essayez adapter et synchroniser.
4-Une fois compiler vous vous trouverez sur une interface d'accueil qui contient deux buttons.
Bouton de réglage : qui n'est pas programmé.
Bouton Trending : Ce bouton permet d'afficher une autre interface sur laquelle figure la liste des dépositoires. Sur cette page vous pouvez paginer sur autre page car on affiche 100 dépositoires par page. Et vous pouvez également faire retour sur la page d'accueil.

Information : Cette application n'affiche que 1000 premiers résultats disponible de GitHub.
Ce qui signifie que vous pouvez seulement paginer sur 10 pages au maximum.
