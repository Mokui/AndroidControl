# AndroidControl

L'application permet d'ajouter des mémos dans une table et de les afficher correctement dans une
liste. Lorsqu'on clique sur un item de la liste, il est affiché dans une nouvelle page, sauf si on est en
mode paysage ET que l'écran fait 600dp de large ou plus, auquel cas il est affiché à droite de la
liste.
L'utilisateur peut également supprimer un mémo (dans la liste et en base de données) lors d'un
swipe vers la droite uniquement.
L'application devra utiliser l'architecture MVVM pour charger et afficher la liste, ainsi que Dagger 2
pour gérer les dépendances.
