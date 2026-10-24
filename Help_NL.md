# Railveal – Help en gebruikershandleiding

**Voor iOS en Android**  
Laatst bijgewerkt: 24 oktober 2026

## Over Railveal

Railveal is een kaartapp voor het bekijken van Nederlandse spoorweginfrastructuur. De app toont openbare gegevens van ProRail boven op een normale kaart. U kunt onder andere sporen, wissels, overwegen, toegangspoorten, hectometerpunten en uw huidige locatie bekijken.

Railveal heeft geen account nodig en gebruikt geen eigen backend.

> **Let op:** Railveal is een informatieve kaartapp. Gebruik de app niet als enige bron voor operationele, veiligheidskritische of toeganggerelateerde beslissingen. Volg altijd de geldende regels, bebording en aanwijzingen ter plaatse.

## De kaart gebruiken

- Sleep met één vinger om de kaart te verplaatsen.
- Knijp met twee vingers om in of uit te zoomen.
- Tik op een zichtbaar object om de details te openen.
- Houd een lege plek op de kaart ingedrukt om daarvan de spoorgeocode en kilometrering te bepalen.
- Sluit een detailvenster met de knop **Sluiten** rechtsboven in het venster.

De app start met Nederland in beeld. Als u locatietoegang toestaat, centreert de kaart bij de eerste geldige locatiebepaling automatisch op uw positie.

## Zoeken

Gebruik linksboven het veld **Geocode, km of adres**. Start de zoekopdracht met de zoekknop op het toetsenbord.

### Zoeken op geocode

Voer alleen het nummer van een ProRail-geocode in, bijvoorbeeld:

```text
122
```

Railveal zoekt dan naar overwegen en toegangspoorten op deze geocode.

### Zoeken op geocode en kilometer

Voer een geocode en kilometerwaarde in, bijvoorbeeld:

```text
122 15.7
122 15,7
```

Een punt of komma als decimaalteken wordt ondersteund. De resultaten worden gesorteerd op afstand tot de ingevoerde kilometerwaarde.

### Zoeken op adres

Voer een straat, huisnummer en/of plaatsnaam in. De geocoderingsvoorziening van het apparaat zet het adres om naar een kaartlocatie. Railveal toont vervolgens nabijgelegen overwegen en toegangspoorten.

Adreszoeken kan per platform of apparaat iets andere resultaten geven.

### Zoekresultaten

- Tik op een resultaat om de kaart erop te centreren en de details te openen.
- Gebruik de wisknop in het zoekveld om de zoektekst, resultaten en foutmelding te wissen.
- De melding **Geen overwegen of poorten gevonden** betekent dat binnen het zoekgebied geen passend object is gevonden.

## Huidige locatie

Tik rechtsboven op **Huidige locatie** om de kaart naar uw positie te verplaatsen.

Op Android verandert deze knop in een kompas zodra de kaart is gedraaid. Tik dan op het kompas om de kaart weer met het noorden naar boven te zetten; daarna wordt de knop automatisch weer **Huidige locatie**.

Wanneer spoorinformatie beschikbaar is, verschijnt onderaan een kaart met:

- de naam van de spoorgeocode;
- nabijgelegen spoornamen tussen vierkante haken;
- de berekende kilometerwaarde.

Voorbeeld:

```text
Huidige locatie
Roosendaal - Breda [BD, BDG]
15,734
```

De weergegeven kilometrering wordt berekend aan de hand van de dichtstbijzijnde ProRail-spoorlijn. Buiten of te ver van het spoor kan geen waarde worden getoond.

## Locatietoestemming

Railveal vraagt alleen om locatietoegang tijdens het gebruik van de app.

- Met toestemming werken automatisch centreren en de huidige-locatie-informatie.
- Zonder toestemming blijven de kaart, lagen, handmatige selectie en zoekfuncties bruikbaar.
- U kunt de toestemming later wijzigen via de privacy- of appinstellingen van iOS of Android.

Op iOS en Android kunt u de beschikbare locatienauwkeurigheid via de systeeminstellingen beheren. Voor een zo nauwkeurig mogelijke kilometrering is een precieze locatie het meest geschikt.

## Kaartlagen

Tik rechtsboven op **Kaartlagen** om het lagenpaneel te openen. De volgende lagen zijn beschikbaar:

### ProRail luchtfoto

Toont de meest recente beschikbare ProRail-luchtfoto als transparante kaartlaag.

### PDOK luchtfoto

Op iOS schakelt u **PDOK luchtfoto** in via het lagenpaneel. Op Android gebruikt u de schakelaar **BRT-kaart / PDOK luchtfoto** om de Kadaster/PDOK BRT Achtergrondkaart te vervangen door de actuele landsdekkende PDOK-luchtfoto. De ProRail-luchtfoto blijft, wanneer ingeschakeld, altijd boven deze ondergrond liggen.

### Kadastrale kaart ProRail

Toont de kadastrale gemeente- en sectiegrenzen, percelen, grondplannen en eigendomskaart van ProRail. Na inschakelen verschijnen een doorzichtigheidsregelaar en de actuele legenda van de ProRail-service. Tik op een zichtbaar perceel om het perceel te omlijnen en onder andere de gepubliceerde eigenaar, perceelsaanduiding, gemeente, sectie, grootte en het onroerende-zaak-ID te bekijken.

### Sporen en wissels

Toont spoorlijnen, wissels en spoor- of wisselbenamingen. Geocodes en hectometerpunten hebben een eigen schakelaar: **Geocodes en hectometers**. Schakel die laag in en zoom voldoende in om de punten en labels te zien.

### Overwegen

Toont overwegen. Overwegen worden bij ver uitzoomen verborgen om de kaart leesbaar te houden.

### Poorten

Toont toegangspoorten langs het spoor. Ook poorten worden bij ver uitzoomen verborgen.

Standaard zijn **Geocodes en hectometers**, **Sporen en wissels**, **Overwegen** en **Poorten** ingeschakeld. iOS gebruikt Apple MapKit als basiskaart; Android gebruikt de Kadaster/PDOK BRT Achtergrondkaart; **ProRail luchtfoto**, **PDOK luchtfoto** en **Kadastrale kaart ProRail** zijn uitgeschakeld.

## Kaartobjecten en details

### Overwegen

Een overweg kan de volgende informatie tonen:

- naam;
- type;
- locatieaanduiding;
- aantal sporen;
- geocodenummer en geocodenaam;
- kilometerwaarde;
- karakter van de overweg.

Een dienstoverpad is niet navigeerbaar en toont daarom geen route- of navigatieknop.

### Toegangspoorten

Een toegangspoort kan de volgende informatie tonen:

- geocodenummer en geocodenaam;
- kilometerwaarde;
- vluchtfunctie;
- of de poort in gebruik is.

### Hectometerpunten

Hectometerpunten verschijnen alleen wanneer **Geocodes en hectometers** actief is en u voldoende bent ingezoomd. Het blauwe punt markeert de exacte broncoördinaat; het label erboven toont de kilometerwaarde.

Tik op een hectometerpunt om de exacte bronwaarde, geocode en eventueel het kmlint te bekijken. Hectometerpunten zijn informatieve referentiepunten en zijn op Android niet navigeerbaar. De huidige iOS-versie toont een aangetikt hectometerpunt technisch als geselecteerde locatie.

### Geselecteerde locatie

Houd een plek op de kaart ingedrukt om **Geselecteerde locatie** te openen. Railveal projecteert de gekozen positie op de dichtstbijzijnde spoorlijn en berekent daaruit de geocode en kilometerwaarde.

### Afstand meten

Tik rechtsboven op de knop met de lineaal om de meetmodus te activeren. Er verschijnt een vast meetpunt in het midden van het scherm. Verschuif de kaart tot dit punt op de gewenste locatie staat en tik in het informatiepaneel op **Meetpunt plaatsen**. Verschuif daarna de kaart naar het gewenste eindpunt; de lijn en afstand in meters veranderen tijdens het verschuiven mee. Tik op **Eindpunt plaatsen** om de meting af te ronden.

Na het plaatsen van het eindpunt toont het informatiepaneel de RD X- en RD Y-coördinaten van het start- en eindpunt. Met de kopieerknop (**Kopieer** op iOS) kopieert u beide coördinaten en de afstand in meters. Kies **Nieuwe meting** om opnieuw te beginnen of tik nogmaals op de lineaalknop om de meetmodus af te sluiten.

De meting geeft de afstand tussen de gekozen punten, geen loop- of autoroute. Ook in objectdetails kunt u beschikbare RD-coördinaten naar het klembord kopiëren.

### Favorieten (iOS)

Tik op de ster in de detailpopup om een object te bewaren of weer te verwijderen. De ster aan de rechterkant van de kaart opent de favorietenlijst, gegroepeerd op geocode en baanvak en gesorteerd op kilometrering. Tik op een favoriet om het object te openen. Favorieten blijven lokaal bewaard na het afsluiten van de app.

### Spoor in Beeld (iOS)

De perspectiefknop in de detailpopup opent de Georizon-webviewer van Spoor in Beeld bij de geselecteerde locatie. Hiervoor worden de RD-coördinaten in de link meegegeven.

## Route of navigatie openen

Routeplanning is beschikbaar voor toegangspoorten, normale overwegen en handmatig geselecteerde locaties. Dienstoverpaden en kadastrale percelen zijn niet navigeerbaar. Op Android zijn ook hectometerpunten uitgesloten van routeplanning. Bij handmatig geselecteerde locaties op of vlak bij het spoor kan Railveal een nabijgelegen poort of overweg als bestemming kiezen. De details vermelden dan **Via** welke toegang de route loopt. Zolang geen geschikte bestemming is bepaald, kan de routeknop ontbreken.

### iOS

Tik op **Navigeer**. Railveal opent Apple Kaarten met de geselecteerde bestemming en een autoroute. In de huidige iOS-versie wordt een aangetikt hectometerpunt als geselecteerde locatie behandeld en kan deze knop daarom zichtbaar zijn.

### Android

Tik op **Route plannen**. Railveal vraagt autonavigatie naar de bestemming aan via een externe app die Google-navigatielinks ondersteunt. Als die niet beschikbaar is, probeert Railveal een geografische locatielink te openen in een geschikte kaartapp. Het gedrag daarna hangt af van de externe app.

Controleer altijd zelf of de bestemming openbaar en veilig bereikbaar is. De aanwezigheid van een routeknop geeft geen toestemming om spoorwegterrein of ander afgesloten terrein te betreden.

### QR-codes en delen

Bij navigeerbare objecten kunt u op de QR-knop tikken en kiezen tussen **Apple Kaarten** en **Google Maps**. De QR-code wordt lokaal gegenereerd en bevat een autoroutelink naar de bestemming, eventueel de gekozen toegang. Scan de code met een ander apparaat om de link daar te openen. De aanbiederkeuze voor de QR-code verandert de gewone navigatieknop niet.

Op Android verschijnt na het openen van de QR-code ook **Deel route**. Hiermee deelt u via het systeemdeelvenster de routelink en objectinformatie, zoals naam, kilometrering en eventuele toegang. Op iOS kunt u de getoonde QR-code laten scannen.

## Siri, Opdrachten en CarPlay (iOS)

Voorbeelden van Siri-opdrachten:

- `Zoek een overweg in Railveal`
- `Welke overwegen zijn er in Railveal`
- `Zoek poort in Railveal`
- `Navigeer naar overweg in Railveal`
- `Navigeer naar poort in Railveal`
- `In Railveal ben ik het spoor bijster`

Geef bij een vervolgvraag bijvoorbeeld `geocode 122 kilometer 15,7` of een straatnaam. Bij meerdere resultaten kunt u een nummer of deel van de naam noemen. De spoorpositie-opdracht gebruikt uw locatie en werkt binnen 100 meter van het spoor; de reactie kan ook de dichtstbijzijnde toegang vermelden.

Wanneer Railveal beschikbaar is op uw aangesloten CarPlay-systeem, kunt u spoorpositie, favorieten en nabijgelegen overwegen of toegangen openen. Navigatie wordt overgedragen aan Apple Kaarten.

## Kaartbronnen per platform

- **iOS:** Apple MapKit als basiskaart.
- **Android:** MapLibre met de Kadaster/PDOK BRT Achtergrondkaart als basiskaart.
- **Beide platforms:** spoorweginfrastructuur, luchtfoto's en kilometrering via openbare ProRail-kaartdiensten.

Door verschillen tussen basiskaarten en geocoderingsdiensten kunnen kaartlabels, adressen en routevoorstellen per platform afwijken.

## Licht en donker thema

Railveal schakelt automatisch tussen een licht en donker uiterlijk op basis van de berekende zonsopkomst en zonsondergang voor het midden van Nederland. De berekening wordt periodiek bijgewerkt.

## Internetverbinding

Voor de basiskaart, ProRail-lagen, objectdetails, adreszoeken en kilometrering is een internetverbinding nodig. Wanneer een dienst tijdelijk niet beschikbaar is, kunnen kaarttegels, objecten of zoekresultaten ontbreken.

## Toegankelijkheid

Railveal ondersteunt VoiceOver op iOS en TalkBack op Android.

- Bedieningsknoppen hebben beschrijvende namen.
- Zoekresultaten worden als één logisch element voorgelezen.
- Detailvelden worden voorgelezen als label en waarde.
- De huidige-locatiekaart wordt als één samenhangende beschrijving aangeboden.

De beschikbare vergroting, contrastinstellingen en tekstfuncties worden verder door iOS of Android bepaald.

## Problemen oplossen

### Mijn locatie wordt niet gevonden

1. Controleer of locatietoegang voor Railveal is toegestaan.
2. Controleer of precieze locatie voor Railveal is toegestaan.
3. Controleer of de locatiediensten van het apparaat actief zijn.
4. Ga naar buiten of naar een plek met beter satelliet- en netwerksignaal.
5. Tik opnieuw op **Huidige locatie**.

### Ik zie geen overwegen of poorten

- Controleer in **Kaartlagen** of de betreffende laag actief is.
- Zoom verder in; objecten worden bij een groot kaartgebied verborgen.
- Controleer uw internetverbinding.
- Het kan voorkomen dat de ProRail-dienst tijdelijk geen gegevens levert.

### Ik zie geen hectometerpunten

- Schakel **Geocodes en hectometers** in.
- Zoom aanzienlijk verder in.
- Wacht kort totdat de punten uit de ProRail-dienst zijn geladen.

### Een zoekopdracht geeft geen resultaten

- Controleer het geocodenummer.
- Probeer zowel `15.7` als `15,7` voor een kilometerwaarde.
- Voeg bij een adres ook de plaatsnaam toe.
- Zoekresultaten bevatten alleen ondersteunde objecttypen, zoals overwegen en toegangspoorten.

### De kilometerwaarde lijkt niet exact

De waarde bij een handmatig geselecteerde of huidige locatie wordt berekend door projectie op ProRail-spoorgeometrie. GPS-afwijking, afstand tot het spoor en brongegevens kunnen het resultaat beïnvloeden. Een aangetikt hectometerpunt toont daarentegen de exacte opgeslagen bronwaarde van dat punt.

### Een kaartlaag blijft leeg

Schakel de laag uit en weer in, beweeg of zoom de kaart en controleer de verbinding. Openbare kaartdiensten kunnen tijdelijk traag of niet beschikbaar zijn.

## Privacy

Railveal heeft geen accounts, advertenties of tracking en bewaart geen locatiegeschiedenis. Kaartgebieden, zoekopdrachten of coördinaten kunnen voor de gevraagde functie rechtstreeks naar ProRail, de basiskaartdienst, de geocoderingsvoorziening of een bewust geopende routeapp worden verzonden.

Zelf opgeslagen favorieten blijven op iOS lokaal bewaard. Siri- en Opdrachten-acties kunnen daar tijdelijk lokaal worden opgeslagen voor overdracht naar de app. Bij het kopiëren komen coördinaten of meetgegevens op het systeemklembord; een QR-code of gedeelde routelink maakt de bestemming toegankelijk voor de ontvanger. De iOS-perspectiefknop opent Spoor in Beeld met de geselecteerde coördinaten.

Lees voor Android de volledige [Nederlandse privacyverklaring](Android/PrivacyPolicy_NL.md). De iOS-privacyverklaring staat in [PrivacyPolicy.md](iOS/Railveal/PrivacyPolicy.md).

## Gegevens en bronvermelding

De optionele PDOK-luchtfoto is op beide platforms beschikbaar, met bronvermelding voor PDOK/Beeldmateriaal. Spoorweginfrastructuurgegevens worden geleverd door ProRail onder **CC BY 4.0**. De Android-basiskaart is de **Kadaster/PDOK BRT Achtergrondkaart**, eveneens aangeboden onder **CC BY 4.0**. Bronvermelding blijft permanent onderaan de kaart zichtbaar.

## Contact

Heeft u hulp nodig of wilt u een fout in de kaart of app melden? Neem dan contact op met:

**FLI**

Vermeld bij een probleem indien mogelijk:

- iOS of Android;
- apparaatmodel en systeemversie;
- wat u probeerde te doen;
- de gebruikte geocode, kilometer of locatie;
- een schermafbeelding zonder gevoelige informatie.
