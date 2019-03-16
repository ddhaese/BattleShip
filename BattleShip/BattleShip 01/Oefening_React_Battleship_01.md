# Oefening React Battleship 01
## Inleiding 

In deze tweede reeks oefeningen gaan we een zeeslag spel maken. Na afloop zal er zo uitzien:

![Battleship.jpg: Screenshot zeeslag](img/Battleship.jpg "Zeeslag")

Deze zeeslag React component is bedoeld om in een side-bar ergens op een website te plaatsen om de bezoekers een tijdverdrijfje je te bieden wanneer ze ergens op moeten wachten of gewoon uit verveling. De afbeelding toont een basis versie van het spel,  later wordt de toepassing uitgebreid met extra opties zoals het bijhouden van scores in een noSQL databank.

## De opdracht

Voor we eraan beginnen moet je op basis van onderstaande analyse zelf eens proberen nadenken over de structuur van het spel.

Analyse:

Bij het opstarten toont het spel een speelveld met de schepen netjes op een rij gepresenteerd. De zijde van het speelveld mag voor deze reeks als constant worden beschouwd (zijde=7) en de vloot ook (1 Carrier van 5 cellen, 1 Battleship van 4 cellen, 2 Cruisers van 3 cellen en 1 destroyer van 2 cellen). Bovenop dit opstart-rooster komt een halfdoorzichtig paneel, net even groot als het speelveld, met de boodschap "Welcome to Battleship" en daaronder een knop "Start". Omdat het paneel halfdoorzichtig is, ziet de speler in de achtergrond de vloot al liggen, maar de cellen van het speelveld kunnen nog niet op muisklikken reageren. Drukt een speler op de start-knop, dan verdwijnt het halfdoorzichtige paneel, worden alle schepen verborgen achter grijze cellen en willekeurig verspreid over het speelveld. De speler ziet nu een rooster van grijze cellen en kan één voor één een cel aanklikken met de muis. Bij elke klik op het speelveld:

- gaat er een teller lopen die onderaan links onder het speelveld wordt getoond (Guesses: #)
- verschijnt er een boodschap rechts van de teller (en ook rechts uitgelijnd t.o.v. speelveld) met het resultaat: "You missed.", "You hit a \<Type van het schip>.", "You sunk a \<Type van het schip>." of "You sunk the fleet!" (niet getoond in de afbeelding hierboven). Bij de aanvang wordt hier de boodschap "Click a square to drop a bomb" getoond.
- verandert de aangeklikte cel (grijs --> boot-ikoontje of 'zee')

Wanneer de ganse vloot is gezonken verschijnt opnieuw het halfdoorzichtig paneel, nu met de boodschap "Thanks for playing Batlleship, your score is <score hier>" en de knop "Again". De eindscore wordt berekend als `afronden ( 100 x [ 1 - ( Aantal klikken - totale bootlengte ) / ( grootte speelveld - totale bootlengte )])`, maar dat is nu eigenlijk nog niet aan de orde.

---

## Antwoord

Voor elke component:

1. Naam van de component:
   > Geef hier je antwoord

   Korte omschrijving van de component:
   > Geef hier je antwoord

   Wat moet er in de state komen:
   > Geef hier je antwoord

   Welke props moet het van bovenaf krijgen:
   > Geef hier je antwoord

1. Naam van de component:
   > Geef hier je antwoord

   Korte omschrijving van de component:
   > Geef hier je antwoord

   Wat moet er in de state komen:
   > Geef hier je antwoord

   Welke props moet het van bovenaf krijgen:
   > Geef hier je antwoord

1. ...
---