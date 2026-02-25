Makerspace Bestelsysteem

Projectbeschrijving
Dit project betreft een webapplicatie voor de Makerspace binnen de school. Het systeem maakt het mogelijk voor studenten om standaard 3D-print producten te bestellen via een online bestelsysteem.
De geplaatste bestellingen worden beoordeeld door een docent. De docent bepaalt welke bestellingen worden goedgekeurd en daadwerkelijk geproduceerd.
Het doel van dit project is het ontwikkelen van een functioneel bestelsysteem met authenticatie, rolverdeling en databasekoppeling.

Functionaliteiten

Studenten:

-Inloggen met studentnummer

-Bekijken van beschikbare 3D-print producten

-Plaatsen van bestellingen

-Inzien van de status van bestellingen

Docenten:

-Overzicht van alle geplaatste bestellingen

-Goedkeuren of afkeuren van bestellingen

-Beheren van orderstatussen

Gebruikte Technologieën

Backend framework: Laravel

Programmeertaal: PHP

Database: Relationele database (bijvoorbeeld MySQL)

Frontend: Blade templates (Laravel), HTML, CSS

Authenticatie: Inlogsysteem op basis van studentnummers

Systeemarchitectuur:
De applicatie is ontwikkeld volgens het MVC-principe (Model-View-Controller), zoals toegepast binnen Laravel.

Globale database-structuur

Voorbeelden van gebruikte tabellen:

-students

-teachers

-products

-orders

-order_status

Relaties:

-Een student kan meerdere orders plaatsen.

-Een order behoort tot één student.

-Een order bevat één of meerdere producten.

-Een docent kan een order goedkeuren of afkeuren.

Installatie:

Clone de repository:

git clone https://github.com/jouw-gebruikersnaam/jouw-repository.git

Ga naar de projectmap:

cd makerspace-bestelsysteem

Installeer de dependencies:

composer install

Maak een .env bestand aan en configureer de databaseverbinding.

Genereer een applicatiesleutel:

php artisan key:generate

Voer de migraties uit:

php artisan migrate

Start de development server:

php artisan serve
Leerdoelen:

Ontwikkelen van een webapplicatie met Laravel

Implementeren van authenticatie en autorisatie

Werken met een relationele database

Toepassen van CRUD-functionaliteit

Ontwerpen van een gestructureerde database

Projectinformatie:

-Opleiding: Software Developer

-School: Davinci 

-Schooljaar: Leerjaar 3

-Auteurs: [Naam/Namen invullen]
