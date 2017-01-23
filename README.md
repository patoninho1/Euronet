# Euronet
















































 







I)	    Présentation du Projet EURONET MRPH

II)		Expressions des besoins
a.	Besoins Clients.
b.	Proposition de Mise en oeuvre.

III)	Organisation administrative et planification des tâches.

a.	Rédaction dossier de spécificités et analyse fonctionnelle.
b.	Création d’un Gantt prévisionnel.
c.	Avancement hebdomadaire du projet.

IV)	Fonctionnement de l’Application

V)	    Programmation/Structure du code

a.	Choix de la plateforme
b.	Création des pages
c.	Structure du code
d.	Gestion du contenu
e.	Problèmes rencontrés

Conclusion

I)	Présentation du Projet MATRIOSHKA


Matrioshka est un projet développé par l’association « Quatorze » Il s’agit d’un mobilier urbain connecté qui permettrait de jouer le rôle de hot-spot Wi-Fi au sein d’évènements nomades à durée éphémère tels que des foires ou festivals. 
Matrioshka est également emblématique des nouveaux modèles de micro-production énergétique et se veut adaptable à différents écosystèmes urbains, pour y transformer les pratiques d’occupation de l’espace public.
Dimensionnée pour alimenter simultanément, à partir d’une énergie renouvelable et gratuite, 4 ordinateurs et 6 téléphones portables. Cet objet possède également une borne d’accès, un routeur WiFi, des prises et ports USB. Dans ce rapport, nous détaillerons les enjeux et problématiques rencontrés lors de la réalisation de l’application de cartographie et les moyens mis en œuvre pour y remédier.




II)	  Expressions des besoins

a.	Besoins Clients.

Les attentes de ce projet étaient nombreuses :
Il fallait que les gérants puissent simplement gérer et visualiser l’ensemble des Matrioshkas en temps réel.
-	Assister le Client à Optimiser la Répartition Géographique des MATRIOSHKA. 
-	Suggérer à l’Utilisateur des Emplacements Stratégiques en tenant compte des différents Obstacles présent sur Place et de la portée des Modules. 
Après que ce dernier ait préconfiguré la Zone qu’il souhaite couvrir.
Mais également un service leur permettant de visualiser les Matrioshkas qu’il a à sa disposition.


b.	Proposition de Mise en oeuvre.


Pour répondre à ces attentes nous sommes concentrés sur quatre points :

-	Une Interface Intuitive et facile d’utilisation :

o	Simplifier au maximum l’application

-	Séparer les Deux Modes d’Utilisations :

o	Administrateur
o	Clients

-	Gérer et Visualiser à distance le parc de Matrioshka :

o	Permettre aux utilisateurs de géolocaliser leurs modules
o	Permettre aux administrateurs d’avoir des informations concernant chaque Matrioshka en service.

-	Optimisation de l’emplacement des modules.

o	Créer à l’aide d’une GoogleMap une carte sur laquelle les utilisateurs pourront positionner leurs Matrioshkas dans le but de les implanter.






III)	Organisation administrative et planification des tâches.

a.	Rédaction dossier de spécificités et analyse fonctionnelle.

-	Le Dossier de spécificité permet de décrire brièvement l’application ainsi que les différents acteurs qui seront amenés à l’utiliser.

-	L’Analyse fonctionnelle décrit en détail l’application et présente chacune de 
Ses différentes parties ainsi que les interactions avec l’utilisateurs. 


b.	Création d’un Gantt prévisionnel.

Dans le but de donner une ligne de conduite au projet, il a été décider de créer un calendrier avec MSProjectManager, il en ressort qu’il a plus ou moins été respecter dans les grandes lignes. Il est très compliqué de se projeter et de planifier des tâches deux mois à l’avance.



Voici un aperçu du Gantt qui a été créé :



c.	Avancement hebdomadaire du projet.

Dans cette partie sera présenté le cahier bord du projet décrivant notre avancement semaine par semaine : 

			Semaine 1 :
-	Création d’un Cloud partagé
-	Recherche de méthodes pour réaliser une Application Android
-	BrainStorming à propos du contenu de l’Application
-	Réalisation d’un Gantt prévisionnel 

Semaine 2 :

-	Création du squelette de l’Application 


-	Réalisation de Dossier de Spécificités
-	Réalisation de l’Analyse Fonctionnelle
-	Choix de l’IDE de développement 
-	Découverte de Android Studio





Semaine 3 :
-	       Création des premières pages de l’Application 
exemples : Page d’accueil, page de login.



Semaine 4 :

-	Création d’un PowerPoint reprenant le squelette qui avait été fait sur un Tableau 











-	Création d’autres pages de l’Application



-	Création de liaisons entre les différentes pages :
http://matrioshka.libcast.com/ma-chaine-5307/phase_de_test_matrioshka1-0-mp4




Semaine 5 :

-	Travaille sur la GoogleMaps et son intégration dans l’Application.
	
Ici il s’agit d’une simple GoogleMaps que nous devrons modifier pour insérer une zone de texte ou des boutons.

 Nous avons inséré un bouton sur la GoogleMaps.





Semaine 7 :

-	Ajouts de la fonction de géolocalisation aux « GoogleMaps ».


Semaine 8 :

-	Finalisation du projet :
http://matrioshka.libcast.com/ma-chaine-5307/phase_de_test_finale












IV)	Fonctionnement de l’Application
L’Application mise en place au cours de ce projet aura pour but premier d’assister l’utilisateur à optimiser la répartition géographique des MATRIOSHKA.
Elle permettra de suggérer à l’utilisateur des emplacements Stratégiques en tenant compte des différents obstacles présents sur place et de la portée des hotspots. 
Après que l’Utilisateur ait préconfiguré la zone qu’il souhaite couvrir.
L’Application propose deux modes d’utilisation.  
-	Utilisateur : permet de créer une carte de placement
-	Administrateur : permet de visualiser (statut de connexion, emplacement) et lister le parc.

Mode Utilisateur de l'Application

 Aperçu du processus permettant de « Créer une carte ».
Mode Administrateur de l'Application























                  

	 Aperçu du mode « Administrateur ».



















V)	Programmation/Structure du code

A.	Android Studio

Le choix de la plateforme de programmation (communément appelée IDE) s’est porté vers Android Studio. 
En effet pour avoir une meilleure visibilité sur l’avancement de l’application, il fallait une IDE présentant une interface graphique (appelée GUI), mais également assez populaire pour faire suffisamment l’objet de tutoriels sur Internet. Malgré quelques aléas et des lenteurs au niveau logiciel, ce choix n’est pas un regret.
Le simulateur présent nativement dans Android Studio étant trop peu fiable et présentant des fonctionnalités en moins comparé à un appareil physique. La décision a été prise de compiler le code sur un appareil Android physique. Dans ce cas il s’agissait d’un Samsung Galaxy Note 2 qui été relié au PC via USB.
Quant au système d’exploitation utilisé il aura été principalement Mac Os X tout au long du projet.

B.	Création des pages

La création des différentes pages que comportera le projet est une étape primordiale, car il s’agit du squelette de l’Application. Voici le procédé à suivre pour la réaliser :

Dans un premier temps il faut « créer un nouveau projet ».

















Ensuite vint le Choix cornélien du « SDK minimum » (sdk est l'acronyme anglais pour Software Development Kit), il s'agit généralement d'un ensemble d'outils d'aide à la programmation proposé aux développeurs par l'IDE, dans laquelle nous allons développer notre projet.
Cette étape est très importante car elle conditionnera notre manière de programmer. 
En fonction de la version choisie il y aura plus ou moins de fonctionnalités.
La version logiciel du Galaxy Note 2 sur lequel sera simulé l’application étant : API 14 Android 4.0 IceCreamSandwich, le projet sera donc développé sous cette même version.




















Après avoir choisie la version sous laquelle développer, il faut désormais choisir 
L’activité de la première page, Android Studio propose plusieurs exemples d’activités.
Cependant on choisira une « Blank Activity », c’est à dire une page vierge.

















La dernière étape de la création du Projet, est de mettre des intitulés aux différents fichiers que comporte le projet.





















Le projet étant totalement créé, visualisons l’interface.
L’essentiel de la création de l’application se déroulement sur cette page.

La seconde étape une fois arrivée aux « layout » sera de supprimer le fichier content_main.xml. 
En effet celui-ci étant le contenu graphique de la page activity_main.xml, nous allons intégrer content_main.xml directement dans activity_main.xml en remplaçant simplement le contenu de l’un dans l’autre. On obtient ainsi ceci :

Une fois la première page créée, il faut reproduire le procédé précédent pour chaque page nécessaire.
Clic droit sur « Layout » > New > Activity > Blank Activity.

















Pour les pages qui intègrent des « GoogleMaps », le procédé pour les créer est légèrement différent.
Clic droit sur « Layout » > New > Google > Google Maps Activity.


Une fois la page créée, il faut renseigner les champs « Hierarchical Parents » et « Package Name ».
C’est-à-dire la page qui permet d’accéder à cette dernière.



Il faut maintenant répéter l’opération pour toutes pages nécessaires à l’Application…

Toutes les pages ont maintenant été créées.
Ci-dessous apparait une page « Activity » GoogleMaps avec son programme Java. 
C’est sur cela que nous allons maintenant nous concentrer.

C.	Structure du code

La structure du Projet est simple, il s’agit de Pages distinctes reliées les unes aux autres.
Chacune de ces pages est composée de deux fichiers principaux : 

-le fichier Java (ci-dessous MainActivity.java) contient les fonctions et les actions que réalise la page : librairies, classes, fonctions utilisées pour exécuter les différents outils présents dans l’activité sont insérées et placées dans ce fichier.

-le fichier XML (ci-dessous activity_main.xml) contient l’aspect et l’interface de la page : zones de textes, images, liste et boutons sont insérés et placés dans ce fichier.



















 

















Voici un aperçu du contenu d’une « activité » : 

Les différents widgets (un widget est un objet ayant une fonctionnalité) insérés dans les fichiers XML.

-	Boutons 
Dans la classe onClick() 
		On affecte au bouton le fait de changer de page lorsque l’on clique dessus.

-	Listes d’éléments


		Le String[] permet de contenir des éléments
		Que nous afficherons sous forme de liste

                    Aperçu de la liste générée par le code ci-dessus.




















Pour les activités comprenant des « GoogleMaps » il a fallu utilisé des classes « FragmentActivity » qui permettent fragmenter la page en plusieurs activités.

Par exemple une des pages « Créer une Carte » l’écran est couper en deux.
-	Une partie « GoogleMaps » 
-	Une partie avec les boutons et les icônes que l’on peut glisser sur la carte.


                                                                         Aperçu d’une page de « Créer une Carte » qui utilise la classe « FragmentActivity ».


















Voici un morceau du code qui génère cette page. 





















 Aperçu de la page d’accueil « Main » de notre   application qui utilise une classe « Activity » simple.

	



















Voici le code de la classe « Main» qui génère la page ci-dessus.
D.	Gestion des permissions

Pour faire fonctionner notre application nous avons besoin d’utiliser certaines options de l’appareil mobile.
Pour avoir accès à ces options nous devons faire appel à des « permissions ».
Les permissions sont utilisées pour demander des droits d’accès à des composants 
 			par exemple : appareil photo, bluetooth, internet, GPS, etc…

Cette permission permet d’avoir accès à la connexion internet de l’appareil.




Ces dernières doivent être répertoriées dans un fichier qui s’intitule AndroidManifest.XML 









E.	Problèmes rencontrés


Un grand nombre des problèmes rencontrés durant ce Projet étaient dû à l’obsolescence.
En effet Google met constamment à jour ses outils de développement rendant ainsi inutilisable certaines fonctions et méthodes, pour les remplacer par d’autres.
Cela a pour principal défaut de faire que des dizaines de tutoriels deviennent inutiles.

Entre les différentes versions d’API pour Android ou les différentes versions de simulateurs de mobile virtuel ainsi que leurs caractéristiques, il aura été difficile dans un premier temps d’être au point niveau versions.

De nombreuses fonctionnalités ont été créées :
-Login de Connexion 
-Outil de mémorisation des Cartes en interne à l’application
-Visualisation des Matrioshkas en direct.
-Listing du Parc des Matrioshkas avec informations les concernant.

Cependant faute de serveur dédié nous n’avons malheureusement pas pu nous concentrer dessus dans le but de les réaliser.

Outre ces challenges, Au travers de cette application nous avons énormément appris sur l’univers Android ainsi que sur le Monde de la création d’application qui a un poids comptable sur l’économie actuelle.
Au final ces petits contre temps nous auront permis de réfléchir d’autant plus sur ce quoi nous avions à faire.

