# SOEX Beroepsproduct
Casusbeschrijving voor SOEX: Solution Exploration

## Vakantieplan app: Triptop

Een applicatie waarmee een vakantietrip gepland kan worden. Een vakantietrip bestaat uit verschillende bouwstenen die aan elkaar gekoppeld kunnen worden. 

Mogelijke bouwstenen zijn 
- Overnachtingen
- Vervoer tussen overnachtingen
- Heen en terugreis
- Autohuur

De bouwstenen kunnen verschillende toestanden hebben: 
- Gepland
- Geregeld
- Betaald
- Niet uitvoerbaar
- Uitgevoerd

Elke instantie van een bouwsteen kan een verschillende externe service nodig hebben. 
Voorbeeld:

- Overnachtingen: de ene wordt via booking geregeld, de andere is in eigen beheer
- Vervoer tussen de ene twee overnachtingen gaat met de auto (via google maps routeplannen), de andere gaat via de boot (via een veerdienst).

### Opdracht in hoofdlijnen

1. Ontwerp maken waarbij gebruik gemaakt moet worden van C4.  
2. Design patterns bestuderen en toepassen. 
3. PoCjes maken van communicatie met één, of twee externe services.

Essentieel in deze casus is dat je niet alleen bedenkt en visualiseert hoe de software eruit moet zien maar deze plaatjes ook voorziet van tekst waaruit keuzes blijken die je hebt gemaakt en het geheel (een software guidebook) voor een andere ontwikkelaar begrijpelijk is. Daarnaast werk je enkele keuzes uit in de vorm van werkende prototypes. 
