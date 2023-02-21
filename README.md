# PHP oefening

## Installatie

> 1. Fork dit project naar je eigen Github repositories
> 2. Clone dit project naar een lokale (niet Onedrive) map.
> 3. Open het project in VS Code
> 4. Open een terminal en type `docker compose up`
> 5. Open je browser en ga naar http://localhost/
> 6. Open PHPMyAdmin door in je browser te gaan naar http://localhost:8000

## Database

> 1. Maak een database genaamd `computerwinkel` met behulp van PHPMyAdmin.
> 2. Importeer of kopieer de `manufacturers.sql` gegevens in de database.


## Database connectie

> 1. Maak een bestand genaamd `database.php`.
> 2. Maak eerst database connectie, gebruik de code van Moodle of [Github Cheatsheet](https://github.com/NOVA-college-Haarlem/Mysqli-cheatsheet)

## Toon de gegevens
> 1. In het bestand manufacturers_index.php schrijf je code om een de database connectie te *importeren*.
> 2. Maak een iteratie met een foreach loop om zo de gegevens in de browser te tonen.
> 3. Laat het resultaat aan de docent zien.

# SQL oefeningen

## Voorbereiding

> 1. Clone het project [Computer Winkel](https://github.com/NOVA-college-Haarlem/computer-winkel) van het Nova College Github Repository.
> 2. Maak een database genaamd `computerwinkel` met behulp van PHPMyAdmin.
> 3. Importeer de sql bestanden in de database
> 4. Maak de ids in elke tabel een primary key
> 5. Maak manufacturer in products al seen foreign key

## Opdrachten

Noteer je antwoorden in `antwoorden.sql` zodat je ze later terug kunt vinden
> 1.	Selecteer de namen van alle producten in de winkel.
> 2.	Selecteer de namen en de prijzen van alle producten in de winkel.
> 3.	Selecteer de naam van de producten met een prijs van minder dan of gelijk aan €200.
> 4.	Selecteer alle producten met een prijs tussen €60 en €120.
> 5.	Selecteer de naam en prijs in centen (d.w.z. de prijs moet worden vermenigvuldigd met 100).
> 6.	Bereken de gemiddelde prijs van alle producten.
> 7.	Bereken de gemiddelde prijs van alle producten met fabrikantId gelijk aan 46.
> 8.	Bereken het aantal producten met een prijs groter dan of gelijk aan € 180.
> 9.	Selecteer de naam en prijs van alle producten met een prijs groter dan of gelijk aan € 180, en sorteer eerst op prijs (in aflopende volgorde) en vervolgens op naam (in oplopende volgorde).
> 10.	Selecteer alle gegevens van de producten, inclusief alle gegevens van de fabrikant van elk product.
> 11.	Selecteer de productnaam, prijs en van alle producten.
> 12.	Selecteer de gemiddelde prijs van de producten fabrikantnaam van elke fabrikant en laat alleen de code van de fabrikant zien.
> 13.	Selecteer de gemiddelde prijs van de producten van elke fabrikant, met vermelding van de naam van de fabrikant.
> 14.	Selecteer de naam en prijs van het goedkoopste product.
> 15.	Voeg een nieuw product toe: Luidsprekers, $ 70, fabrikant 2.
> 16.	Update de naam van product 8 naar "Laser Printer".
> 17.	Pas 10% korting toe op alle producten.
> 18.	Pas 10% korting toe op alle producten met een prijs groter dan of gelijk aan $120.
