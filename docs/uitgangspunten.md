# Uitgangspunten

Via het [forum](https://woodworking.nl/threads/een-freestafeltje-het-eerste-project.39623/) wordt besproken welke wensen/eisen we stellen aan diverse onderdelen van de freeslift.

Omdat niet iedereen gezegend is met een enorme werkplaats is een relatief compact model handig. Een kleiner model voor de kleine werkplaats maar die dan ook op een soort van onderstel kan worden gemonteerd. Hierbij ben je dan vrij om te bepalen welke voor jou ruimte toepasbaar is.

Er is ook nog een keuze om het zo te maken dat je het aan je bestaande werkbank kan vastmaken, of met een klein onderstel dat op een tafel kan, of helemaal met grote poten zodat het op de grond kan staan. Bij de laatste 2 versies kunnen we dan nog iets toevoegen als lades om frezen en aanverwanten op te bergen.

- Suggestie: Opbouw uit modules
- Suggestie: Het is slechts een raamwerk dat je aan de bank bevestigt
- Suggestie: Een kleine makkelijk op te bergen versie zou ook mijn voorkeur hebben, i.v.m. de beschikbare ruimte
- Suggestie: Haak/ haken er aan maken om het op te hangen. Stukje wand kan wel eens vrij zijn in een grage/ schuur/ e.d.
- Suggestie: Waar ik baat bij zou hebben is een ontwerp dat een leuke balans laat zien tussen kant en klare onderdelen en zelfbouw.

Door middel van geparameteriseerd ontwerpen kan men afwijken van standaard gekozen afmetingen en posities etc. Zie [mogelijke parameters](ontwerp.md#parameters) voor de mogelijkheden.

## Werkblad

### Afmeting

Suggestie: 60 x 40 cm
Via parameters **mod_breedte**, **mod_diepte** en **blad_overstek** kunnen alternatieve waarden opgegeven worden. Parameter **blad_overstek** kan ook 0 mm ingesteld worden zodat er geen overstek is.

De achterzijde heeft geen overstek zodat de freestafel ook geschikt wordt voor wandmontage.

### Materiaal

Er wordt uitgegaan van 18 mm betonplex. Dit is reeds glad en (voor gebruikelijke toepassing) vlakker dan multiplex. Bij toepassen van een inlegplaat van 10mm blijft een ondersteuningsrand van 8 mm over.

- Suggestie: Maak het blad wat dikker, dan kan de plaat van de openlift daarin vallen.
- Suggestie: Een belangrijke zaak voor iedereen die een zware freesmotor in zijn lift zet bedenk dat 18 mm betonplex gaat doorhangen en als je zoals ik er een incra stofbak onder hebt hangen dan is dat lastig te verstevigen.
- Suggestie: zou het nog zinnig zijn om in plaats van betonplex een plaatje hpl als toplaag te nemen?

Via parameter **blad_dikte** kan de totale dikte worden opgegeven. Bijvoorbeel 2 x 12mm multiplex wordt 24mm.

### Vlak / vlakheid

Het blad van de freestafel wordt ondersteund door rechte latten om te zorgen dat het blad over de lengte en de breedte vlak is. Dit wordt ook wel *torsion box* genoemd.

De ombouw van de torsion box komt overeen met de module/onderkast afmetingen. Het binnenwerk van de torsion box is gevormd met een offset van 20mm rond de inlegplaat.

Via parameter **torsionbox_hoogte** kan de hoogte van de latten worden opgegeven. Parameter **mod_hoogte** bepaalt de hoogte van de ombouw van de torsion box. Dit kan handig zijn, bijvoorbeeld als men wil dat de module/onderkast luchtdicht wordt voor betere onderafzuiging.

Montage van het blad aan de torsion box staat open / ter discussie.

## Inlegplaat / Freeslift

Parameter **inlegplaat_breedte** en **inlegplaat_diepte** bepalen de buitenmaten van de inlegplaat, waarbij **inlegplaat_hoekradius** de radius van de hoeken aangeeft. Parameter **inlegplaat_dikte** is de dikte van de inlegplaat en is tevens de minimale hoogte wat uit de bovenkant van het blad gehaald (gefreesd) moet worden.
Via parameter **inlegplaat_center_offset** kan de positie van de inlegplaat ten opzichte van de voorkant van de tafel worden vestgelegd. Vanuit de breedte gezien zit de inlegplaat in het midden.

- Suggestie: een losse inlay te maken zodat het voor meer gereedschappen te gebruiken is, bijvoorbeeld decoupeerzaag.

Naar wens kunnen de parameters ingesteld worden op afmetingen van een losse inlay.

### Geleiders / klemvoorziening

- Suggestie: maak er een miterslot in dan kun je met een slede veilig kleine stukken frezen

### Frees wisselen

Frees verwisselen van bovenaf.

### Hoogteverstelling

Hoogte verstelling van bovenaf.

### Stofafzuiging van onderen

## Aanslag

- Suggestie: langsgeleider met verstelbare 'opening'.
- Suggestie: Een aanslag die verstelbaar is in 2 rails links en rechts, middels een aantal ondersteuningen haaks

### Stofafzuiging

## Nullastschakelaar

- Suggestie: Als het tafeltje wat groter wordt zou ik de bediening naar de buitenzijde van het tafeltje willen brengen. Hierdoor hoef je niet steeds onder het tafeltje te "kruipen".

## Kast

- Suggestie: Afstel gereedschap moet in op aan de tafel zitten.
- Suggestie: opslag voor freesbitjes

## Extra

Wat ik zelf nog wil en ga maken is een drukmodule. Tweeledig: door de constante horizontale en verticale druk wordt er nauwkeuriger gefreesd.
