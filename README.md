WP-Quick-Install 1.2.3
================

WP Quick Install est un script permettant d'installer WordPress en seul clic (t�l�chargement, d�compression, installation de plugins, cr�ation base de donn�es, etc...). 

Pour le mettre en place, t�l�chargez l'archive et rendez-vous sur le fichier *wp-quick-install/index.php*

Changelog
================

1.2.3
-----------

* Correction d'un bug sur le param�tre d'activation du SEO

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
