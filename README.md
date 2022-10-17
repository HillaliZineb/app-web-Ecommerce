# App-web-Ecommerce
Notre projet consiste à créer une application web shopping en ligne. En
effet, cette application offre à l’administrateur l’opportunité de faire la
publicité de ses produits en ligne à travers un accès web, explorer le
catalogue pour les visiteurs, et de passer les commandes pour les clients.
D’une autre part, l’administrateur du site peut effectuer plusieurs
fonctions telles que la modification du produit, l’ajout des fournisseurs et
des catégories.

Réalisation

Partie administrateur:

   1.Page d’authentification
   ![image](https://user-images.githubusercontent.com/98094518/196182193-7aa38800-3f69-42db-b5da-1efae514945b.png)

   La méthode d’authentification de l’administrateur est semblable à celle du client ,mais elle effectue ses tests sur la table admin, en comparant les données saisies avec celles enregistrées dans la base de données.
	Après le succès de son authentification, l’administrateur est redirigé vers un tableau de bord, proposant plusieurs méthodes à l’administrateur pour gérer son site.
  
   2.Page Dashboard :
   
  ![image](https://user-images.githubusercontent.com/98094518/196182306-aad2452b-e823-44ba-b5ef-af33c883a1da.png)

   3.Page d’ajout du fournisseur :
   ![image](https://user-images.githubusercontent.com/98094518/196182428-3d96b2de-bb75-4947-a6c4-dcc7e78ab0e7.png)
   
   4.Page d’ajout du produit :
   ![image](https://user-images.githubusercontent.com/98094518/196182928-39b04ea7-04f1-4c13-ad30-334ed398c232.png)
   
   5.Page d’ajout d’une catégorie :
   ![image](https://user-images.githubusercontent.com/98094518/196183131-5d1957ff-6221-4168-ba2a-f9af9dca59bc.png)
   
   6.Page d’affichage des clients :
   ![image](https://user-images.githubusercontent.com/98094518/196183290-2f10021a-5555-4935-9b67-3aa6ee85d7f0.png)

   7.Page d’affichage des produits :
   ![image](https://user-images.githubusercontent.com/98094518/196184099-0b5d1a22-de1b-4b64-b6fb-74adabd4114d.png)
Partie client:
   1.Page d’accueil:
   ![image](https://user-images.githubusercontent.com/98094518/196184336-e53b6f9d-5824-4fab-b990-e7373b037d67.png)
    La page d'accueil est la couverture de l'application .Cette interface, avec ses marges publicitaires, reflété d'une manière explicite l'esprit commercial et dynamique du site.
Dans un premier temps, on repère le Logo du site, la première figure qui attire l'attention du visiteur/client, dont le choix est bien justifié dans le paragraphe précédent. Ensuite on croise la barre de recherche, qui génère ses résultats depuis la table de produits, ayant comme critères de filtre de recherche un caractère saisie dans la barre deux caractères , trois...ou le nom complet du produit. Juste après l'outil de recherche , on trouve l'icone panier ,qui nous redirige vers notre panier de produit si et seulement si connecté, juste à coté il y a l'icone administrateur , qui lui propose de s'authentifier. Ainsi que les boutons inscription et authentification pour les clients ou futurs clients. Juste au dessous de la barre de navigation, se trouve le menu de catégorie , qui nous redirige vers les catalogues de produits de chaque catégorie ou sous catégorie. A sa droite se situe le cadre d'animations des publications promotives.En navigant vers le bas, on perçoive la section promotrice d'un seul produit par catégorie, généré automatiquement de depuis la table produit, dont le pourcentage de promotion est le plus pertinent.et vers la fin de la pigeon trouve le fameux footer qui propose des infos des invitations au partenariat la liste des fournisseurs…

   2.Page du catalogue:
   ![image](https://user-images.githubusercontent.com/98094518/196185112-4c1b8ab9-5298-4234-8e83-484f8a8a2226.png)
   Ces pages contiennent des produis générés automatiquement de la base de données, possédant un Button détails, qui
affiche la description du produit, ainsi qu'un boutton ajouter au panier, pour les clients authentifiés.

   3.Page panier:
   ![image](https://user-images.githubusercontent.com/98094518/196186564-2a9512a3-d624-4ee6-9990-1006b5e9202b.png)
   le panier est une option pour les clients, cette dernière affiche un tableau décrivant le produit futurement acheté, proposant des options tel l'incrémentation de la quantité , la décrémentation ,la suppression d l'article, ou la suppression totale du panier. Cette interface est générée depuis la base de donnée ,et toute option parmi ce qui précède effectue des opérations explicite sur la table concerné.
   Et enfin on croise le bouton validation du panier qui fait transmettre les données confirmés par le client, vers la table commande, et suite cette opération génère une facture sera générée.
   
  4.Page inscription :
  ![image](https://user-images.githubusercontent.com/98094518/196186782-ce5828c8-4bd8-4218-bf31-1a250b2ee805.png)
  La page d'inscription affiche un formulaire à remplir dont tous les champs sont obligatoire, après avoir testé si l'adresse email existe déjà sur la base de donnée, le client sera redirigé vers la page d'accueil.Sinon,un message d'erreur sera affiché.
  5.Page d’authentification :
  ![image](https://user-images.githubusercontent.com/98094518/196187271-e9e2b4f9-0d10-4e17-91de-3377fec09b5b.png)
  La page d'authentification propose aux visiteurs de s'authentifier, si le visiteur est déjà inscrit la page le redirige vers l'accueil en tant que client authentifié, sinon on lui affiche un message d'erreur.


 
