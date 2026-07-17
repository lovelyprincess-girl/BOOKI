# Booki

Booki est un site de recherche  d'hébergements et d'activités. C'est un projet d'intégration web réalisé en HTML et CSS, à partir d'une maquette fournie par une équipe Produit fictive.

Le site permet de rechercher un hébergement dans une ville, de consulter une liste d'hôtels populaires et d'hébergements classiques, de filtrer par thématique (économique, familial, romantique, animaux autorisés), et de découvrir des activités à faire sur place. Le site est responsive : il s'adapte à un écran d'ordinateur, de tablette ou de mobile.

Il s'agit d'une maquette statique. Le formulaire de recherche ne fait pas de vraie recherche, et les liens des cartes ne mènent nulle part pour l'instant. L'objectif du projet était uniquement de valider l'interface.

## Technologies utilisées

Le site est fait en HTML et CSS uniquement, sans framework (pas de Bootstrap, pas de Tailwind), sans préprocesseur (pas de Sass), et sans JavaScript. La mise en page est réalisée avec Flexbox. La police utilisée est Raleway, importée depuis Google Fonts, et les icônes viennent de la bibliothèque Font Awesome.

## Responsive

Le site a été développé d'abord pour ordinateur, puis adapté pour tablette et mobile grâce aux media queries en CSS.

- Au-dessus de 1024px : affichage ordinateur
- Entre 768px et 1024px : affichage tablette
- En dessous de 768px : affichage mobile

La largeur du contenu est limitée à 1440px maximum, pour éviter que le site s'étire trop sur un très grand écran.

## Structure du projet

index.html
css/style.css
images/

## Comment voir le site

Il suffit d'ouvrir le fichier index.html dans un navigateur, aucune installation n'est nécessaire.

## Remarques

Le code a été vérifié avec les validateurs officiels du W3C (HTML et CSS) et ne contient aucune erreur. Aucune propriété CSS n'est écrite directement dans le HTML, tout passe par le fichier style.css.

## Auteur

Projet réalisé par Lucrèce MOUSTAPHA, dans le cadre de ma formation de Développeur Web chez OC.
