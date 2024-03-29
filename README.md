# soex-opdracht-1
Casusbeschrijving voor SOEX: Solution Exploration

## Casusvoorstel Vakantieplan app

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
- Niet uitvoerbaar?
- Uitgevoerd?

Elke instantie van een bouwsteen kan een verschillende externe service nodig hebben. 
Voorbeeld:

- Overnachtingen: de ene wordt via booking geregeld, de andere is in eigen beheer
- Vervoer tussen de ene twee overnachtingen gaat met de auto (via google maps routeplannen), de andere gaat via de boot (via een veerdienst).

 
### Opdracht (globaal)

1. Ontwerp maken waarbij gebruik gemaakt moet worden van C4.  
2. Domeinmodel maken 
3. Design patterns bestuderen en toepassen bij 1 en 2. 
4. PoCjes maken van communicatie met één, of twee externe services op basis van 1, 2 en 3.

### Opmerkingen

- Aanroepen van externe services en dat integreren met het domein is nieuw tov DoEx.
- Is een ontwerpkeuze om de aanroep van externe services in de back-end te doen of in de front-end? Zou wel leuk zijn. 
  - Ik ben zelf geneigd om externe aanroepen die state kunnen veranderen sowieso in de back-end te doen, maar queries die alleen extra info opvragen misschien niet.
- Ik zou het erg leuk vinden als studenten elkaars werk op ontwerpniveau zouden kunnen testen. Dus kunnen we studenten al "iets" meegeven waarmee ze kunnen kijken of een ontwerp uberhaupt kan werken? 
  - Misschien kun je een aantal abstractere processen definieren die in het ontwerp moeten terugkomen. Bijvoorbeeld vertalen van een bericht van een externe service naar een aanroep van het domein. Wie doet dat?  

