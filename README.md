# Data Visualisations | Les collections du Moma depuis 1929

Giorgia Vocino, Marion Charpier Tomas Chaineux, Aude Eychenne - février 2023
Ce projet a été réalisé dans le cadre du cours "Données, Web de données et exploitation" au master 2 "Technologies numériques appliquées à l'histoire" de l'Ecole nationale des chartes.L'objectif du projet a consisté à enrichir les dataset d'oeuvres et d'expositions du Moma afin de pouvoir rendre compte de deux axes de développement du musée depuis 1926 : sa politique d'acquisition et son activité d'exposition.

# Jeux de données
Les trois sets de données d'origine du projet sont disponibles sur le github du Moma :

Le jeu de données Artists contient 15 243 enregistrements d'artistes ayant des œuvres dans la collection du MoMA et catalogués avec les métadonnées suivantes : nom, nationalité, sexe, année de naissance, année de décès, Wiki QID, Getty ULAN ID.

Le jeu de données Artworks contient 140 848 enregistrements des œuvres qacquises dans la collection du MoMA et cataloguées avec les métadonnées suivantes : titre, artiste, date de réalisation, support, dimensions, date d'acquisition. Certaines entrées comportent des informations incomplètes et sont notées comme "non approuvées par le conservateur".

Le jeu de données Exhibitions répertorie 1 788 expositions, représentant toutes les expositions connues organisées au musée de 1929 à 1989. Les métadonnées sont nombreuses et les essentielles retenues pour le projet sont les suivantes : ExhibitionID, ExhibitionNumber, titre de l'exposition dates de début et fin d'exposition,  Wikidata QID.

# Création de nouveaux jeux de données
Les données initiales ont été complétées de la façon suivante :

    - Le jeux de données artists du Moma a été enrichi avec les personnes référencées comme artistes de Wikipédia via requêtage Sparql afin d'augme,ter les références Wikidata du fichier de départ.(Jeu de départ 3244 WikiId artistes / Jeu d'arrivée: 4002 WikiId artistes.)
    - Le jeu de données artworks a été enrichi avec ce jeu d'arrivée artistes Moma-Wiki.
    - Le jeux de données exhibitions du Moma a été enrichi avec les expositions référencées dans Wikipédia via requêtage Sparql afin de rendre compte également des expositions présentées au musée depuis 1989.(Jeu de départ 1666 titres d'expositons / jeu d'arrivée: 2438 titres d’expositions.)
       
# Data Visualisations
Les datavisualisations sont disponibles ici :

## Visualisation de l’activité d’acquisition  des œuvres au fil des années à travers les six départements du Moma

## Evolution de la représentation des nationalités dans les collections 

## Proportion d’artistes exposés de leur vivant depuis la création du musée jusqu’en 1989

## Evolution de l'activité d’exposition du musée de sa création jusqu'aujourd’hui


_(juste en dessous des badges sympatiques à placer)_

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)  [![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](http://forthebadge.com)

Une petite description du projet

## Pour commencer

Entrez ici les instructions pour bien débuter avec votre projet...

### Pré-requis

Ce qu'il est requis pour commencer avec votre projet...

- Programme 1
- Programme 2
- etc...

### Installation

Les étapes pour installer votre programme....

Dites ce qu'il faut faire...

_exemple_: Executez la commande ``telnet mapscii.me`` pour commencer ensuite [...]


Ensuite vous pouvez montrer ce que vous obtenez au final...

## Démarrage

Dites comment faire pour lancer votre projet

## Fabriqué avec

Entrez les programmes/logiciels/ressources que vous avez utilisé pour développer votre projet

_exemples :_
* [Materialize.css](http://materializecss.com) - Framework CSS (front-end)
* [Atom](https://atom.io/) - Editeur de textes

## Contributing

Si vous souhaitez contribuer, lisez le fichier [CONTRIBUTING.md](https://example.org) pour savoir comment le faire.

## Versions
Listez les versions ici 
_exemple :_
**Dernière version stable :** 5.0
**Dernière version :** 5.1
Liste des versions : [Cliquer pour afficher](https://github.com/your/project-name/tags)
_(pour le lien mettez simplement l'URL de votre projets suivi de ``/tags``)_

## Auteurs
Listez le(s) auteur(s) du projet ici !
* **Jhon doe** _alias_ [@outout14](https://github.com/outout14)

Lisez la liste des [contributeurs](https://github.com/your/project/contributors) pour voir qui à aidé au projet !

_(pour le lien mettez simplement l'URL de votre projet suivi de ``/contirubors``)_

## License

Ce projet est sous licence ``exemple: WTFTPL`` - voir le fichier [LICENSE.md](LICENSE.md) pour plus d'informations



