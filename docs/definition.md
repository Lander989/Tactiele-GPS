## Definition

# Iteratie 1 
### Doestellingen

In het kader van deelopdracht 2 (Definition Phase) werd een eerste reeks low-fidelity prototypes ontwikkeld. Het doel van deze iteratie was om te onderzoeken of het onderliggende concept een tactiele kaart als ruimtelijk referentiekader begrijpelijk, bruikbaar en zinvol is voor personen met een visuele beperking. De focus lag hierbij expliciet op “Design the Right Thing”, vóór verdere technologische verfijning.

De kerninzichten en onderzoeksvragen waren:

- Hoe verloopt de interpretatie van tactiele kaartinformatie door gebruikers
- De manier waarop gebruikers een tactiel oppervlak exploreren
- De leesbaarheid en resolutie van de kaarten
-	Welke functie zijn nodig om het product bruikbaar te maken? (In de zin van: inzoomen op kaart, geluid instellen, bewegen met de kaart,…)
- De geschiktheid van verschillende interactiemethoden en draagwijzen

De werking gaat als volgt:

<p align="center">
  <img src="../img/StoryBoard.jpg" width="75%">
</p>

### Materiaal & methoden
De eerste wave bouwen we op uit meerdere kleine testen waarmee we onze deelvragen beantwoorden. Hierna testen we het totaal concept.

#### 1. Orientatie N = 10

Dit onderzoek verkent hoe gebruikers navigeren met tactiele oriëntatie en in welke mate een tactiele routeweergave helpt bij het afleggen van een parcours. De test werd uitgevoerd met tien geblinddoekte jongeren zonder visuele beperking, wat een zorgvuldige interpretatie van de resultaten vereist. De deelnemers kregen de opdracht een parcours zo snel mogelijk af te leggen, met behulp van een tactiele LEGO-kaart met vereenvoudigde routeweergave en/of verbale instructies. Er waren twee groepen: één met tactiele kaart en verbale instructies, en één met enkel verbale instructies. Tijdens de test werden gedrag en benodigde tijd geregistreerd.

<p align="center">
  <img src="../img/LegoNavigatieTest.jpeg" width="50%">
</p>

#### 2. Kaart afmetingen N = 2
Protocol

We willen nagaan welke kaartresolutie het best tactiel waarneembaar is. Hiervoor legden we de testpersoon meerdere tactiele kaarten voor die allemaal hetzelfde patroon weergeven, maar verschillen in resolutie.

De testpersoon verkende elke kaart afzonderlijk en beschreef wat zij voelde. Aangezien alle kaarten hetzelfde patroon bevatten, is het niet zinvol om ze te vergelijken op basis van herkenningssnelheid of accuraatheid. In plaats daarvan focusten we op de subjectieve ervaring van de testpersoon. We vroegen expliciet welke kaart volgens haar het duidelijkst en meest leesbaar aanvoelde. Deze test voerden we uit samen met twee blinden.

<p align="center">
  <img src="../img/Resolutie.jpeg" width="50%">
</p>

#### 3. Draagwijzen N = 6 

Blinden en slecht zienden lopen bijna altijd met de stok rond hierdoor is er dus nog maar een van hun handen vrij wanneer ze op stap gaan. Daardoor willen we testen op welke manier het product kan gedragen worden. Hiervoor hebben we drie opstellingen: het product los in de ene hand , het product bevestigd aan de arm met behulp van een brace, het product met daaraan een lanyard voor rond de nek te draggen.
<p align="center">
  <img src="../img/armband opstelling.jpg" width="25%">
</p>
<p align="center">
  <img src="../img/lanyard opstelling.jpg" width="25%">
</p>
De testpersonen kregen elk individueel alle verschillende opstellingen in de hand en mochten daarmee dan ook rondlopen. De meningen van iedereen werden ook in groep besproken.

#### 4. interactiemethoden N = 6 

Het product moet natuurlijk te besturen zijn , hiervoor zijn dan ook verschillende inputs voor nodig. Voor dit te testen werd gebruikgemaakt van een adaptief prototype met velcro waar verschillende soorten knoppen, draaiwielen, sliders en joysticks aan bevestigd kunnen worden.
<p align="center">
  <img src="../img/input test.jpg" width="25%">
</p>
Deze kunnen dan georiënteerd worden zoals de gebruiker ze het liefst wilt.

<p align="center">
  <img src="../img/test kaart.jpg" width="50%">
</p>



#### 5. Concept validatie N = 2 

De test bestaat uit een vooraf uitgestippeld traject dat deelnemers afleggen met behulp van opeenvolgende tactiele kaarten. Elke kaart toont een begin- en eindpunt; bij aankomst ontvangen deelnemers een nieuwe kaart. Tijdens het interpreteren van de kaarten wordt de think-aloud-methode toegepast. De kaarten zijn noordgericht en deelnemers worden geïnformeerd wanneer hun GPS-richting hiermee overeenkomt. Indien nodig grijpen we in voor veiligheid of bij foutieve interpretaties, die meteen worden toegelicht. Tijdens de test evalueren we hoe goed deelnemers hun omgeving begrijpen op basis van de kaarten.


<p align="center">
  <img src="../img/Kaart traject.jpeg" width="50%">
</p>

### Resultaten

Bij het testen van het totaalconcept kwamen meerdere fundamentele problemen aan het licht. Hoewel de gebruikers in staat waren om het traject te interpreteren, bleek louter een globale richtingsaanduiding onvoldoende om zich met vertrouwen te verplaatsen. De complexiteit van de reële omgeving overstijgt de vereenvoudigde weergave van de kaart, waardoor cruciale context ontbreekt tijdens het wandelen.


- Een Google Maps-achtige top-down representatie is niet intuïtief voor blinde gebruikers

- Effectieve oriëntatie vereist een dynamische, meedraaiende kaart in combinatie met een duidelijk referentiepunt

- Routeplanning is mogelijk, maar vraagt om bijkomende, duidelijk onderscheidbare feedback

- Schaal, obstakels en hoogte-informatie zijn bepalend voor de bruikbaarheid van de kaart

- De kaart ondersteunt het initiële beslismoment, maar biedt onvoldoende ondersteuning bij het opvolgen van de beweging tijdens het traject

Design Requirements:

- D1.4 Orientatie/richting van de route weergeven
- D2.2 Cognitieve belasting moet zo laag mogelijk zijn
- D2.3 bruikbaar na een uitlegsessie 
- D2.6 De bedieningsknoppen moeten een voelbare range hebben
- D2.8 Het product moet met 1 hand bruikbaar zijn
- D2.9 Contrast en kleur aanpasbaar aan voorkeur van gebruiker
- D4.1 Het product moet het zelfvertrouwen van de gebruiker versterken

### Conclusies & implicaties

De pin matrix blijkt cognitief belastend en verwarrend. Hoewel gebruikers nog steeds globale route-informatie kunnen afleiden  zoals rechtdoor, links of rechts  valt het concept na zo’n beslismoment grotendeels uiteen. Er ontbreekt continuïteit en context om verder te navigeren. Wanneer we schaal verkleinen om deze context te geven. Door de schaal te verkleining wordt de straat- en omgevingslayout te abstract, waardoor de weergegeven informatie moeilijk te interpreteren en praktisch nauwelijks bruikbaar wordt. 

In essentie blijft er een pijl over die een richting aangeeft.
Hiernaast willen we nog eens dieper ingaan op wat een blinde nodig heeft om comfortabel en zelfzeker een route te bewandelen. Dit bekijken we in iteratie 2.


# Iteratie 2
In deze wave willen we volgend concept onderzoeken:

<p align="center">
  <img src="../img/Storyboard_W2.jpg" width="100%">
</p>

Hierbij willen we ook antwoord op volgende vragen:
1.	Welke informatie is daadwerkelijk nodig om blinden en slechtzienden comfortabel en met vertrouwen te begeleiden tijdens het navigeren?
2.	In welke situaties en mentale toestanden zou een blinde gebruiker dit product effectief willen gebruiken? 
3.	Is het mogelijk om blinden en slechtzienden effectief te sturen door uitsluitend (of voornamelijk) richting aan te geven met een pijl, en zo ja, onder welke voorwaarden

### Materiaal & methoden N = 2 
We doen dit aan de hand van enkele interviews gevolgt door usability testing.
Tijdens de interviews gaan we nog eens dieper in op de noden van de gebruikers en wanneer zo een toestel handig zou zijn. 

Bijkoment gaan we op wandel om een simpel pijlprototype te analyseren. Voor deze fase hebben we twee blinden en een begeleidster geraadpleegt.

<p align="center">
  <img src="../img/PijlPrototype.jpeg" width="75%">
</p>

<p align="center">
  <img src="../img/Wegwijzer in het wild.jpeg" width="75%">
</p>

### resultaten

Navigatie steunt op zelfvertrouwen, herkenningspunten, herhaling en begeleiding. Voor een blinde persoon zijn de witte stok en een gsm om in noodgevallen hulp te kunnen inschakelen onmisbare hulpmiddelen.

De wereld van blinden is echter zeer divers: geen enkele blinde heeft dezelfde ervaringen, vaardigheden of noden. Tot nu toe kwamen wij voornamelijk in contact met een relatief zelfredzame groep. Een begeleider gaf echter aan dat er ook veel mensen zijn die zonder begeleiding nauwelijks durven bewegen. Voor deze groep zou het wegwijzerconcept een duidelijke meerwaarde kunnen hebben, omdat het actieve ondersteuning en houvast biedt tijdens het navigeren.

Meer zelfzekere gebruikers hebben daarentegen minder nood aan voortdurende begeleiding en eerder aan een hulpmiddel dat hen waarschuwt in rand- of uitzonderingssituaties. Het pinmatrixconcept lijkt vooral geschikt voor gebruik in een thuisomgeving, waar gebruikers een route vooraf kunnen verkennen, voelen en instuderen. In die context is het toestel bovendien niet beperkt door omvang of draagbaarheid.


