# Chartres-ToBook

Projet de fin d'étude Wild Code School 1ère promo Chartres (durée 2 mois)

Etudiant : Thomas Javanaud - Omar Kennouche - Tony Palaquer - Dorian Walck

1 Portage d'un projet php procédural vers le framework symfony 2.8

2 Développement de nouvelles fonctionnalités (emailing, autocompletion recherche adresse, notation)

Technologies utilisées: 
- [Symfony](https://symfony.com/)
- [Google Maps JavaScript API](https://developers.google.com/maps/?hl=fr)
- [jQuery](https://jquery.com/)
- [Bootstrap](http://getbootstrap.com/)
- CSS
- HTML 5

## Captures d'écrans
*Accueil*

![Accueil](https://raw.githubusercontent.com/WildCodeSchool/Chartres-ToBook/master/screenshots/screenshot_Accueil_-_ToBook_-_20160907192942.png)

*Résultats de recherche*

![Résultats de recherche](https://raw.githubusercontent.com/WildCodeSchool/Chartres-ToBook/master/screenshots/screenshot_Rechercher_-_ToBook_-_20160907193007.png)

*Détails d'un établissement*

![Détails d'un établissement](https://raw.githubusercontent.com/WildCodeSchool/Chartres-ToBook/master/screenshots/screenshot_Club_House_-_HOTEL_CAPRICORNE_-_ToBook_-_20160907193023.png)

## Installation

    git clone https://github.com/WildCodeSchool/Chartres-ToBook.git tobook
    cd tobook
    ./chmod.sh
    composer install

Importer la base de données depuis _db/flo_latest_db.sql
Puis lancer le script de mise à jour du schéma :

    php app/console doctrine:schema:update --force
    
