<h1>Compte Rendu du projet de l'activité pratique 4 intitulé unsecured-hospital-app</h1>
  Réalisée par:Qnais Asmaa
  <h3>Plan</h3>
  <ul>
 <li> La logique du JPA</li>
 <li>les fonctionnalités de l'application</li>
 <li>L'authentification</li>
 <li>Page d'acceuil</li>
 <li>Ajouter Patient</li>
 </ul>
 <h3> La logique du JPA</h3>
 JPA (Java Persistence API) est une API Java standardisée qui fournit un cadre pour la gestion de la persistance des données. La logique du JPA repose sur la définition d'entités, qui sont des objets Java qui représentent les tables d'une base de données relationnelle. Les entités sont mappées aux tables de la base de données, ce qui permet de faciliter la création, la mise à jour et la suppression des données.

Le JPA fournit également des repositories, qui sont des interfaces qui définissent des méthodes pour la gestion des entités. Les méthodes de ces repositories permettent de rechercher, d'insérer, de mettre à jour et de supprimer des entités. Les repositories peuvent être personnalisés en ajoutant des méthodes pour effectuer des opérations spécifiques à l'application.

L'utilisation de la logique du JPA permet de simplifier la gestion de la persistance des données dans les applications Java en fournissant un cadre pour la création et la manipulation d'objets Java qui représentent les données stockées dans une base de données relationnelle.
 <h3>les fonctionnalités de l'application</h3>
 L'application envisagée consiste en un système de gestion de patients qui utilise Spring Boot et JPA pour la persistance des données. Les administrateurs de l'application pourront gérer les informations des patients, tandis que les utilisateurs ordinaires ne pourront que consulter la liste des patients. Les principales fonctionnalités de l'application incluent l'ajout, la suppression et la modification des patients, ainsi que l'affichage des patients sous forme de tableau.

Pour faciliter la visualisation des patients, l'application proposera une fonctionnalité d'affichage paginé des patients dans un tableau, permettant aux utilisateurs de naviguer facilement dans la liste des patients et de rechercher des patients spécifiques en utilisant des filtres tels que le nom ou le prénom.

L'application permettra aux administrateurs de se connecter à un compte sécurisé avec des autorisations spécifiques pour effectuer des opérations de gestion des patients. Ils pourront ainsi ajouter de nouveaux patients en fournissant des informations et modifier les informations des patients existants. La suppression des patients sera gérée de manière sécurisée, en s'assurant que seuls les administrateurs autorisés peuvent effectuer cette opération.

Il convient de noter que seuls les administrateurs auront accès aux opérations de modification ou de suppression des patients, tandis que les utilisateurs ordinaires ne pourront que visualiser la liste des patients sans pouvoir effectuer de modifications.

L'application sera conçue de manière modulaire et extensible en suivant les principes d'une application fermée à la modification et ouverte à l'extension. Elle sera également sécurisée, en utilisant l'authentification et l'autorisation pour garantir que seuls les utilisateurs autorisés peuvent effectuer des opérations de gestion des patients.
<h3> L'authentification</h3>
![App](https://github.com/asqn/unsecured-hospital-app/blob/main/image/adm.PNG)
En utilisant Spring Security, nous avons implémenté un système d'authentification solide qui garantit que seuls les utilisateurs autorisés peuvent accéder à notre application. Nous avons également mis en place des fonctionnalités avancées, telles que la gestion des rôles et des autorisations, afin de garantir que les utilisateurs ne peuvent accéder qu'aux ressources qui leur sont spécifiquement autorisées.
Pour accéder à l'interface il suffit de se connecter soir autant qu'admin2 ou user11 et taper le password 1234.
<h3> Page d'acceuil</h3>
Cette page est sous forme d'une liste des patients avec diffétents attributs tel que id,nom,date,score et malade.On peut chercher des patients à travers leurs nom pour mieux faciliter la recherche au sein de l'application;il existe d'autres options tel que la modification des attributs et la suppression des patients

