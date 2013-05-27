## Deployd backend pour mobile-angular.

Nécessaire au bon fonctionnement de mobile-angular.
Pour pouvoir lancer le serveur, il faut intaller deployd. Pour ce faire, il existe des installeur sur le site de deployd (http://deployd.com/download.html), sinon on peut l'installer avec Node Package Manager.
Une fois deployd installé, le serveur se lance en utilisant la commande dpd à la racine du projet.

`dpd`

## Notes

Le serveur dira sur quel port il se lance (2403 par défaut). En allant à l'adresse http://localhost:[port]/dashboard, on peut ajouter des données dans les collections disponibles. Il faudra au moins une ligne dans les collections Vehicles et Persons pour que l'application fonctionne correctment.
