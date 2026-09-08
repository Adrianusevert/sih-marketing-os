# SIH Groep Marketing OS

Marketingdashboard voor de werkmaatschappijen van SIH Groep: campagnes, taken, marketingkalender, KPI's en budget in één overzicht.

## Gebruik

Het dashboard is één bestand: `index.html`. Het werkt in Chrome en Edge zonder server en zonder installatie.

1. Download `index.html` (of open de gepubliceerde link).
2. Open het bestand in de browser.
3. Gegevens worden automatisch bewaard in de browser op het apparaat waarop je werkt.

Bij de eerste start staat er fictieve voorbeelddata in. Klik op "Voorbeelddata wissen" voordat je met echte gegevens werkt.

## Gegevens delen met collega's

Gegevens staan per browser en per apparaat. Delen gaat via het menu Gegevens links onderin:

- Exporteren (JSON): maakt een bestand met alle gegevens.
- Importeren (JSON): leest zo'n bestand in en vervangt de huidige gegevens.

Maak wekelijks een export en bewaar die op een gedeelde locatie. Dat is ook de back-up.

## Onderdelen

- Dashboard: kerncijfers, actieve campagnes, openstaande taken, aandachtspunten en planning voor de komende 30 dagen.
- Werkmaatschappijen: budget, verantwoordelijke en doelstellingen per bedrijf.
- Campagnes: planning, budget, leads, ROI, evaluatie en vervolgstap. Zoeken, filteren en sorteren op elke kolom.
- Taken: acties met eigenaar, deadline, prioriteit en koppeling aan een campagne. Afvinken met het selectievakje.
- Marketingkalender: maandoverzicht van publicaties, events en campagnestarts.
- KPI's: maandmetingen van websitebezoek, leads, conversie en kosten per lead, met grafieken.
- Budget: jaarbudget, toewijzing en besteding per werkmaatschappij en per campagne.

## Beperkingen

- Geen gelijktijdig werken in dezelfde gegevens: iedere gebruiker heeft een eigen kopie.
- Geen koppeling met externe systemen.
- Wie de browsergegevens wist, wist ook het dashboard. Exporteer regelmatig.

## Techniek

Eén HTML-bestand met ingebouwde Chart.js 4.4.1 (MIT-licentie). Geen afhankelijkheden op internet, behalve de lettertypen (vallen terug op systeemlettertypen zonder verbinding).
