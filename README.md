# Adimeo

Tout le contenu HTML de la page se trouve dans le fichier **index.html**.

Le dossier **img** contient toutes les images de la page.

La page s'appuie sur les deux polices d'écriture suivantes :
- **Open Sans**, pour l'ensemble de la page comme indiqué sur la maquette. Source *Google Fonts*.
- **FontAwosome 4.7**, pour l'ensemble des pictogrammes présents dans la page. Source : voir dossier *font-awesome-4.7.0*. 

Le fichier **style.css** regroupe toutes les feuilles de styles de la page.
Il a été organisé comme si les autres pages devaient être intégrées.
Les feuilles de styles sont hiérarchisées à l'aide de commentaires de la manière suivante :
- **normalizer**, contient les balise HTML reconnus par la W3C. Ces feuilles de styles permettent de contrer les propriétés CSS appliquées par défauts par les navigateurs et ainsi créer une mise en formes applicables sur l'ensemble du site.
- **home-page common contents**, regroupe des feuilles de styles pouvant être appliquées n'importe où dans la page d'accueil afin de réduire les doublons.
- **header**, contient la mise en forme du header.
- **first-block**, contient la mise en forme du situé entre le *header* et le *second-block*.
- **second-block**, contient la mise en forme du block *Nos Formations*.
- **third-block**, contient la mise en forme du block *La recherche au sein de l'ENTPE*.
- **fourth-block**, contient la mise en forme des blocks *Actualités* et *Agenda*.
- **footer**, contient la mise en forme du block *footer*.