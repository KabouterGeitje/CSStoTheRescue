# CSS tot the Rescue 2023 - 2024

## Logboek per week

<details>
  <summary>week 1</summary>
  
  ## Wat heb ik gedaan?
Allereerst hebben we het gehad over allemaal 'nieuwe' features van CSS. De groep was verdeeld in kleinere groepen en iedereen kreeg een andere feature om onderzoek naar te doen en dit te presenteren. Het was heel leuk en interessant om te zien wat er allemaal nog meer mogelijk is met CSS en ik heb heel veel zin in dit vak!

We moeten voor de eindopdracht kiezen uit 4 cases. Ik heb gekozen voor een soort morph versie van case 1 & 2. Ik wil een flipperkast maken met CSS. Onmdat je geen random pad kunt zetten met CSS wil ik het niet laten draaien om de bal. De bal zal wel weggeschoten kunnen worden, maar dat pad zal vooral statisch zijn, als in dat hij altijd hetzelfde pad aflegt. Verder is de flipperkast wel helemaal klikbaar. Alle features waar de bal normaal tegenaan komt en wat een geluid of effect zou moeten veroorzaken is nu te veroorzaken door er op de klikken, hoveren, etc. Mocht alles vrij soepel verlopen dan wil ik graag dat je bepaalde onderdelen van de flipperkast kunt aanpassen waardoor de effecten van dat deel van de flipperkast ook veranderen. Ik heb nog niet helemaal visueel hoe ik het eruit wil laten zien, maar ik denk dat ik gewoon begin met maken en er zo wel achterkom hoe ik alles precies wil hebben, omdat ik anders te veel tijd kwijt ga zijn aan het design.

Hieronder de schets die ik heb gemaakt tijdens de les:

![schetsen](/docs/images/flipperkastSchets.jpg)
</details>

<details>
  <summary>week 2</summary>
  
  ## Wat heb ik gedaan?

</details>

<details>
  <summary>week 3</summary>
  
  ## Wat heb ik gedaan?
Ik ben verder gegeaan met het uitwerken van mijn idee. Ik heb de planeten die ik met Sanne gemaakt had vorige week in mijn eigen ontwerp verwerkt. Daarna wilde ik de verschillende containers in mijn ontwerp de goede maten en plek geven
in een grid. Toen bleek dat mijn h1 naar boven verdween, want mijn main was ook een grid en bij het groter worden van mijn scherm, gebeurde dat, toen heb ik dit naar een flexbox omgezet, en dit hielp.

![h1](/docs/images/h1_verdwijnt_naar_boven.png)

Daarna wilde ik mijn containers in mijn hoofdcontainer positioneren met grid.
Hier heb ik lang mee gepuzzeld en toen ik dacht te weten hoe ik het allemaal wilde doen, bleek dat als één van mijn containers de andere overlapte, dat het hele grid raar ging doen en vervormde. Toen besloot ik het grid ingeiwkkelder te maken en op basis van het grid de content een grootte te geven. 

![divs](/docs/images/Divs_positioneren_misschien_met_ingewikkelder_grid.png)

![divscode](/docs/images/Divs_positioneren_misschien_met_ingewikkelder_grid_code.png)

Dit hielp enorm en werkte zoals ik wilde. Alleen kan het hele flipperkastje nu ook gesquished worden als je het scherm abnormaal klein maakt, maar ik dacht, dit gaat toch niet gebeuren op een normaal scherm, dus vond ik het niet zo erg.

![gridraster](/docs/images/Lijnen_uitzetten_voor_mezelf.png)

hieronder wat ik tot nu toe heb:

![totnutoe](/docs/images/tot_nu_toe.png)

![totnutoeklein](/docs/images/tot_nu_toe_klein.png)

</details>

<details>
  <summary>herkansing</summary>
  
  ## Wat heb ik gedaan?
Ik kon pas weer werken aan dit vak na HCD en API. We kregen een week voor alle herkansingen. Hierdoor had ik weinig tijd over, maar ik heb mijn uiterste best gedaan om er iets moois van te maken. Ik heb zo hard doorgewerkt dat ik in de tussentijd geen screenshots heb kunnen nemen, maar omdat ik alles net nog heb gedaan, kan ik er wel iets over vertellen!

Ik moest zo goed als alle styling nog doen en de animaties bedenken en maken. Het voelde als een enorme uitdaging om dit in een paar dagen te moeten doen, maar ik heb alles gegeven wat er nog in zat na de andere vakken.

Ik begon met de slurf die ik samen met Sanne had gemaakt. Aangezien me dat perfect leek om mee te beginnen. Het was alweer een tijdje geleden dat ik dit met Sanne had uitgevogeld, dus ik moest er weer opnieuw naar kijken, vóór ik het echt weer begreep, maar door te experimenteren, kwam ik er gauw achter wat de logica er achter precies was. Ik had alleen 1 probleempje. mijn buis-elementen hebben geen width of height, maar hebben vorm dankzij een grid. Hierdoor moest ik telkens goed zoeken wat nou precies de transform-origin moest zijn. Ik heb gewoon geëxperimenteerd hiermee en hierdoor de antwoorden gevonden.

![slurf](/docs/images/buisMetSanneMaarAndersProcentenpng.png)

Ik heb de elementen stuk vóór stuk vormgegeven. Eerst de vormen bepaald, daarna de kleuren, daarna de details in de styling pas en daarna de animaties.

Ik wilde graag mijn flippers laten bewegen met mijn toetsenbord, maar ik had hier uiteindelijk geen tijd meer voor. Ook zijn mijn hersenene zo op, dat ik het gewoon niet meer kan opbrengen.

Ik wilde eigenlijk de bal laten ontploffen, maar heb hier helaas ook geen tijd meer gevonden, ik heb hem wel laten stuiteren, want de bal niet animeren van een pinbal machine is wel heel stom.

Mijn focus was ook helemaal niet het spel van de pinbal machine, maar dat het juist een ander soort machine werd. Eentje die niet logisch is, maar rare dingen doet en waarmee je dus moet spelen (door de hoveren of te klikken)

Ik had veel meer animaties willen toevoegen. De mooiste animatie die ik heb vind ik de raket. Ik wilde eigenlijk het gat waarin hij verdwijnt ook nog animeren, maar daar ahd ik dus ook geen tijd meer voor.

Ik heb wel gebruik gemaakt van een container query en de hovers heb ik genest in het desbetreffende element.

Ik had elk element een class gegeven. Deze heb ik op het einde verwijderd. Vaak gingen dingen stuk, dus ik heb veel moeten zoeken naar de goede selectors.
Uiteindelijk heb ik 1 class laten staan, omdat mijn animatie kapot ging. (de belangrijkste animatie ook nog)

Ik ben al met al toch heel blij en trots op wat ik heb gemaakt. Ik vind deze minor heel veel en ook vaak lastig, waardoor ik snel overweldigd ben en in een soort freeze state terecht kom. Ik stond meerdere keren op het punt om het op te geven, maar ik me na elke huilbui weer rechtgezet en ben doorgegaan. Of het nu een voldoende wordt of niet, ik ben trots op hoe ik gewerkt heb.

hieronder het eindresultaat

![eindResultaat](/docs/images/eindResultaat.png)

</details>

