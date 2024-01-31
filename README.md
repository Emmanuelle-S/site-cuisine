# Site Cuisine

## _Design_
- J'ai gardé le design de base que l'on retrouve sur kes captures d'écran.
- J'ai essayé de me rapprocher au mieux des couleurs avec [cet outil de séléction de couleur](https://imagecolorpicker.com/fr).
- Concernant les images elles proviennent de [Pixabay](https://pixabay.com/fr/), elles sont libres de droit. Téléchargement au format le plus petit pour la page d'acceuil.

## _Construction HTML/CSS_

Constitué d'un header, main et footer
- __Général__ : Essai de création de classes générales réutilisables comme ``.d_flex - display: flex;``, ``.padd_16 - padding: 16px;``, ``.padd_8 - padding: 8px;``, ``.margin_b - margin-bottom: 8px;`` ... Je n'ai pas encore attaqué la méthode BEM.

- __Header__ : 2 blocs, une ``nav`` et un ``form``. Parent mis en ```display: flex;```, puis enfants en ```flex-wrap: wrap;``` pour le responsive.

- __Main__ :

    - Page d'accueil : 
        - Création d'un conteneur parent mis en ```display: flex;```, puis à l'interieur de plusieurs ``article`` pour chaque recette, avec la propriété ```flex-wrap: wrap;``` pour le responsive.
        - Utilisation de [ce site](https://shadows.brumm.af/) pour les ombrages sur les cartes recettes.
        - Centrage du ``main`` avec les propriétés ``max-width: 1200px;`` et ``margin: auto;``
    - Page Register : 
        - Même principe, mais avec un ``max-width: 900px;``
        - Image mise en ``background-image``

- __Footer__
    - Création d'une ``div`` parent pour le ```display: flex;```, et de 3 ``section`` pour les enfants et le ```flex-wrap: wrap;``` pour le responsive.
    - Image mise en ``background-image``

- __Media Queries__

Utilisation seuelement pour le format mobile, et changer la disposition du ``justify-content`` et de la taille de police.

- __Notions à approfondir__
    - propriété ``flex`` pour le ``basis``, ``shrink`` et ``grow``
    - les media queries
    - les ``background-image``

