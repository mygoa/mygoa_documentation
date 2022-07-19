Installation sur poste de travail de la partie serveur
=====

Installation de Intelij 
------------
Intelij est un IDE qui nous permet de créer et exécuter du code en java.
https://www.jetbrains.com/fr-fr/idea/download/#section=windows

Installation de Java
------------
La partie serveur que ce soit le projet avec selenium ou l'api ont été codé en java. Son installation en version 17 peut se faire via le lien:
https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html
Il faudra penser à ajouter l'exécutable au path

Installation d'une base de données Mysql
------------
Pour fonctionner, les différents serveurs ont besoin d'une base de données MYSQL sur le port 3306, il faudra créer une base de données "joboffer"
Pour régler l'accès à cette bdd, aller dans le fichier configuration.properties. Il faudra y configurer l'identifiant et le mot de passe de la base de données. 
https://dev.mysql.com/downloads/installer/

Installation de git et de maven
------------
Ces outils permettront de garder le projet à jour. 

Téléchargement du repo github
------------
Utilisez git clone avec les repositories voulues, ainsi que le token github données lors de votre arrivée.

Installation des dépendances avec Maven
------------
Une fois dans le dossier du projet, faire:

.. code-block:: console

  mvn compile
