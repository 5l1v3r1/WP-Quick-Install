WP-Quick-Install 1.2.5
================

WP Quick Install est un script permettant d'installer WordPress en seul clic (t�l�chargement, d�compression, installation de plugins, cr�ation base de donn�es, etc...). 

Pour le mettre en place, t�l�chargez l'archive et rendez-vous sur le fichier *wp-quick-install/index.php*

Changelog
================

1.2.5
-----------

* Possibilit� de supprimer le contenu ajouter par d�faut apr�s l'installation de WordPress (article, page et liens).
* Possibilit� d'ajouter des pages sans passer par l'administration � partir du fichier data.ini 
* Mise � jour du fichier php.ini

1.2.4
-----------

* Ajout de deux options de debug : "Afficher les erreurs � l'�cran" (WP_DEBUG_DISPLAY) et "Ecrire les erreurs dans un fichier de log" (WP_DEBUG_LOG)

1.2.3
-----------

* Correction d'un bug sur le param�tre d'activation du SEO
* Suppression automatique des fichiers licence.txt et readme.html

1.2.2
-----------

* Suppression de toutes les fonctions exec()
* D�zip de WordPress et des plugins avec la class ZipArchive de PHP
* Utilisation des fonctions scandir() et rename() pour d�placer les fichiers de WordPress

1.2.1
-----------

* V�rification des droits d'�criture sur le dossier parent
* Ajout d'un lien vers l'admin et le site en cas de succ�s

1.2
-----------

* Possibilit� de pr�-configur� le formulaire � l'aide d'un fichier data.ini


1.1
-----------

* Optimisation diverses du code


1.0
-----------

* Commit Initial
