# CBS Open Data v3
In deze repository zijn codevoorbeelden te vinden van het gebruik van de [CBS StatLine Open Data v3](https://www.cbs.nl/nl-nl/onze-diensten/open-data). Deze versie van de CBS Open Data API is gebaseerd op het [OData 3](https://www.odata.org/)-protocol. 
Het CBS innoveert continu en werkt momenteel aan een nieuwe versie van de API die OData 4 implementeert. Meer informatie en codevoorbeelden voor deze nieuwe versie zijn in de repository [CBS Open Data v4](https://github.com/statistiekcbs/CBS-Open-Data-v4) te vinden.

Er wordt beschreven hoe datasets kunnen worden gedownload met metadata, hoe deze gekoppeld kunnen worden, hoe filters en selecties werken en er is een voorbeeld uitgewerkt van een thematische kaart.

## Codevoorbeelden
Voor elke taal is er een aparte map met daarin codevoorbeelden. De talen die momenteel ondersteund worden zijn
* R (zie ook het package [cbsodataR](https://github.com/edwindj/cbsodataR)),
* Python (zie ook het package [cbsodata](https://github.com/J535D165/cbsodata)).
* CSharp (alleen een basics voorbeeld)
* JavaScript

Elke map bevat
* basics: het downloaden van een tabel, het koppelen van metadata en het downloaden van een selectie van een tabel. Deze code hoort bij de [snelstartgids](https://www.cbs.nl/nl-nl/onze-diensten/open-data/statline-als-open-data/snelstartgids) op de CBS-website. 
* thematic map: het koppelen van geodata van PDOK met CBS-data om een kaart te maken. Deze code hoort bij de handleiding over [cartografie](https://www.cbs.nl/nl-nl/onze-diensten/open-data/databank-cbs-statline-als-open-data/cartografie) op de CBS-website. 
* time series graph: het bewerken en het maken van grafieken van tijdreeksen. Deze code hoort bij de handleiding over [tijdreeksen](https://www.cbs.nl/nl-nl/onze-diensten/open-data/databank-cbs-statline-als-open-data/tijdreeksen) op de CBS-website.

## Werken met geodata
De geobestanden die nodig zijn voor thematische kaarten worden door het CBS gepubliceerd via [PDOK (Publieke Dienstverlening Op de Kaart)](https://www.pdok.nl/datasets). Deze geodata is te downloaden in verschillende bestandsformaten zoals Shapefile en GeoJSON en het is ook mogelijk om de bestanden geautomatiseerd op te halen met de API. In de codevoorbeelden wordt gebruik gemaakt van de API. Meer informatie over de geo-API is te vinden in [de documentatie](https://pdok-ngr.readthedocs.io/).

## Licentie
Op alle datasets van het CBS en alle codevoorbeelden is de licentie Creative Commons Naamsvermelding van toepassing. Als onderdeel van Creative Commons Naamsvermelding is het bij hergebruik verplicht te vermelden dat de gegevens afkomstig zijn van het CBS. Meer informatie is te vinden in de [Disclaimer Open Data](https://www.cbs.nl/-/media/statline/documenten/disclaimer-open-data-v-2.pdf?la=nl-nl).



