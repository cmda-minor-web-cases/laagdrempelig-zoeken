# Laagdrempelig Zoeken

![Visual]()

## Inhoudsopgave
  * [Beschrijving](#beschrijving)
  * [Opdrachtgever](#opdrachtgever)
  * [Design challenge](#design-challege)
  * [Data](#data)
  * [Planning](#planning)
  * [Licentie](#licentie)

## Beschrijving
Zoeken op internet is moeilijk voor veel mensen. Denk bijvorbeeld aan het niet goed snappen van zoektaal (trefwoorden, boolean), vage zoektermen en resultaten die niet aansluiten, of nog erger: niet juist. Over het algemeen betekent minder digitaal vaardig minder mee kunnen komen als digitaal burger, wat een belangrijk onderdeel van burgerschap is inmiddels. 

Informatie zoeken/vinden en delen is core business van de openbare bibliotheek voor de Amsterdammer en we willen graag gebruikmaken van nieuwe techologie die hier verbetering in kan aanbrengen. De ontwikkeling van Natural Language Processing als onderdeel van AI (chatgpt, bard, etc) heeft het laatste half jaar een enorme ontwikkeling doorgemaakt als shippalble tech. Wij denken dat dit heel veel hulp kan bieden om gebruikers sneller en beter te faciliteren met het zoeken vinden van de juiste informatie. Met NLP wordt de natuurlijke taal omgezet in entiteiten die weer doorzoekbaar zijn in onze catalogus api. Dit vergt ook aanpassing op de interface van de zoekomgeving, resultaten staan nu in een klassieke lijst (Zie ook oba.nl/zoeken) hoe kan dit meer een onderdeel worden van het conversatational model of een andere afgestemde weergave (zie ook obajunior.nl, of een prototype van conversational search: https://aitestbed.github.io/zoekchat/ of de prototypes van studenten SE PAD (Link volgt))

## Opdrachtgever
De Stichting Openbare Bibliotheek Amsterdam (OBA) is een culturele instelling, die zich ten doel stelt het vrije verkeer van informatie in de Amsterdamse samenleving te bevorderen. Een belangrijk onderdeel hiervan is het digitaal zoeken en vinden van informatie uit onze of partner collecties. Denk hierbij niet alleen aan boeken of dvd’s maar ook aan activiteiten, cursussen, stadsarchief, en overheids/gemeente-informatie. We zetten nieuwe technologie in om deze materialen beter doorzoekbaar/vindbaar te maken en om de Amsterdammer kennis te laten maken met deze nieuwe technologie. 

## Design challenge
Het doel van dit project is een webinterface voor de OBA waar bezoekers in gewone mensentaal hun vraag kunnen stellen (NLP), en vervolgens de relevante materialen / antwoorden (NER) uit de API (OBA-API). De webinterface interface is afgestemd op natuurlijke conversatie (chat, whatsapp, etc) en past aan aan de doelgroep op de website van de OBA en in begrijpelijke taal een antwoord krijgen op hun vraag.

### User stories
1) Als gebruiker van de zoekinterface van de OBA, wil ik met natuurlijke taal mijn vraag stellen, zodat ik op laagdrempelige wijze relevante resultaten terugkrijg 

2) Als gebruiker van de zoekinterface van de OBA, wil ik een omgeving waarin ik op 1 plek de digitale conversatie aanga met de OBA, zodat ik zowel zoeken, vragen als chat in 1 omgeving kan doen (conversational model) 

3) Als gebruiker van de zoekinterface van de OBA, wil ik een webinterface die goed aansluit bij een conversatiebeleving zowel voor het vragen als de antwoorden en resultaten, zodat

## Data
Content kan worden otsloten via de REST API van de OBA

## Planning
In de eerste week van de meesterproef is een briefing met de opdrachtgever en begeleiders. Wekelijks wordt aan de opdrachtgever een prototype gedemonstreerd en de volgende stappen besproken. Tussentijds kunnen via Teams vragen gesteld worden.

## Licentie
This project is licensed under the terms of the [MIT license](./LICENSE).
