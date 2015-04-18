# bureau_avocats


                                    Application De Gestion D’avocat
			


Table des matières
I.	Contexte et définition du problème :	3
II.	Objectif :	3
III.	Périmètre	3
IV.	Besoin Général	4
V.	Spécification Fonctionnelle	5
VI.	Besoin techniques :	9



I.	Contexte et définition du problème :

Un bureau d’avocat a tendance de recevoir de plus en plus d’affaires à gérer. Ce qui rend la gestion un peu difficile et pose un problème de coordination entre les différents avocats du bureau…. De plus, lorsque l'on doit partager des informations entre collègues, on le fait par email, mais cela devient vite le fouillis : on ne retrouve pas les messages, chacun possède sa méthode de classement et pas de suivi permanent. Et comme pour les années à venir la relation client est l’un des points les plus importants il est de notre devoir de garantir à notre client une satisfaction total soit niveau suivie d’affaire ou possibilité de contact.

II.	Objectif :

Nous voulons offrir un meilleur service aux clients à l'aide d'un véritable outil de gestion des demandes soit du côté des avocats ou le déroulement et la visibilité d’avancement des affaires. Aujourd'hui le taux de satisfaction est à 70%, nous visons les 90% un an après la mise en place du nouvel outil.

III.	Périmètre

 

IV.	Besoin Général 

Il existe des scénarios qui doivent être intégrer dans l’application pour répondre complètement aux besoins des clients :
1.	Fonction Principal : gestion de client
Un client doit être dans la capacité d’accéder à un compte qui le lui est déduit avec un login et mot de passe, dans la plateforme le client peut modifier ces informations personnels, modifier son mot de passe, une visibilité sur l’avancement de ces affaires en cours et enfin contacter l’avocat qui prend en charge l’affaires.
	Création de compte client
	Modifier profil du compte client
	Supprimer compte client
	Consultation d’avancement d’affaires
	Contacter les avocats




2.	Gestion des avocats
L’avocat doit pouvoir accéder à son compte avec un login et mot de passe, avoir la possibilité sur la plateforme dédier de modifier les coordonnées de son contact, répondre aux clients et mettre à jour l’état des affaires et les détails les concernant
	Création de compte
	.Modifier Profil avocats
	Supprimer compte
	Mise à jour d’état d’affaires 
	Répondre aux clients

3.	Gestion des affaires
Sur la plateforme affaires le client pour faire une nouvelle demande, clôturer une affaire, avoir les détails de facture, l’avocat peut accepter ou refuser une nouvelle demande d’affaire, établir la facture et clôturer une affaire.
	Effectuer une nouvelle demande d’affaire
	Clôturer une affaire
	Accepter/ refuser une affaire
	Consulter une facture
	Etablir une facture

 
Diagramme de classe


V.	Spécification Fonctionnelle 


Fonction : Création de compte
Objectif:	Avoir un compte dédié pour l’utilisateur
Description:	Ouverture d’un compte pour l’utilisateur lui permettant d’effectuer des manipulations selon les droits 
Contraintes/ règles de gestion:	Le service n'est valable que pour les clients et les avocats, un mode dégradé sera prévu plus tard pour les prospects. Plusieurs vus disponible selon l’utilisateur (clients / avocats)
Niveau de priorité:	Priorité haute




Fonction : Supprimer compte
Objectif:	Permet de ne plus avoir des comptes non nécessaires
Description:	La possibilité de supprimer son compte 
Contraintes/ règles de gestion:	Le service n'est valable que pour les clients et les avocats, un mode dégradé sera prévu plus tard pour les prospects. Plusieurs vus disponible selon l’utilisateur (clients / avocats)
Niveau de priorité:	Priorité Moyenne 


Fonction : Modifier Profil (compte)
Objectif	Flexibilité pour changement d’informations
Description	Pouvoir changer ces informations personnelles 
Contraintes/ règles de gestion	Le login ne peut pas être changé 
Niveau de priorité	Priorité haute

Fonction : consulter affaire
Objectif	Une meilleure visibilité sur l’avancement des affaires
Description	Consulter l’avancement des affaires en temps réel
Contraintes/ règles de gestion	----------------------------------------------------------------------
Niveau de priorité	Priorité haute


Fonction : Contact
Objectif	Des réponses sur mesure pour le client et a fur et mesure de l’avancement de l’affaire
Description	Le client peut contacter l’avocat assigné à son affaire, l’avocat à la possibilité de répondre à tous les messages reçu 
Contraintes/ règles de gestion	Le client peut contacter seulement l’avocat ou les avocats assignés à ces affaires 
Niveau de priorité	Priorité haute


Fonction : Modifier état d’affaire
Objectif	Classification des affaires selon l’état et urgence
Description	L’avocat peut mettre à jour l’état des affaires 
Contraintes/ règles de gestion	L’avocat peut mettre à jour seulement les affaires attribué à lui
Niveau de priorité	Priorité haute


Fonction : Nouvelle demande d’affaire
Objectif	Pouvoir facilement attribuer une nouvelle demande d’affaire
Description	Le client peut faire une nouvelle demande d’affaire  
Contraintes/ règles de gestion	Nombre maximum d’affaire simultané pour un seul client ne pas dépasser quatre affaires
Niveau de priorité	Priorité haute


Fonction : Clôturer une affaire
Objectif	Pouvoir facilement Clôturer une affaire
Description	Le client/ avocat peut clôturer une affaire
Contraintes/ règles de gestion	Le client ne peut pas clôturer une affaire en cours et qui sa facture n’est pas encore payer, l’avocat ne peut pas clôturer une affaire tant que le client à payer la facture
Niveau de priorité	Priorité haute

Fonction : Accepter/refuser une affaire
Objectif	Meilleur gestion de calendrier d’avocat et d’affaires 
Description	L’avocat peut accepter ou refuser une demande d’affaire selon son calendrier
Contraintes/ règles de gestion	-------------------------------------------------------------------------------------------
Niveau de priorité	Priorité haute

Fonction : consulter/éditer la facture
Objectif	Meilleur visibilité des charges d’une affaire 
Description	Le client peut consulter les détails d’une facture, l’avocat peut établir ou modifier les factures 
Contraintes/ règles de gestion	L’avocat ne peut pas changer une facture déjà payer 
Niveau de priorité	Priorité haute


VI.	Besoin techniques :

L’application doit être développée avec la technologie Asp.net MVC (Web Application Framework) et choisir comme Template le mode MVC (Model View Controller).
Ne faut pas oublier d’utiliser la méthode agile Scrum pour organiser le développement du produit ce qui permettra d’avoir un cadre de travail permettant de répondre aux différents problèmes changeants tout en livrant de manière productive et créative un produit de la plus grande valeur possible.
