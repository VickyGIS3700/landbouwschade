# LandBouwSchade-app 
een applicatie voor steden en gemeenten om de landbouwschadedossiers te helpen verwerken<br>
ideaal voor de controle onderweg <br>
Gebruik het stappenplan.

GIS-SOFTWARE (FOSS)<br>
Qgis 3.4 https://www.qgis.org/nl/site/forusers/download.html <br>

PLUGINS VOOR QGIS3.4 <br>
lat lon tools > https://plugins.qgis.org/plugins/latlontools/ <br>
geopunt-plugin > http://www.geopunt.be/voor-experts/geopunt-plug-ins/qgis-plugin<br>
QField Sync >https://plugins.qgis.org/plugins/qfieldsync/<br>

VOORBEREIDINGSPROJECT IN QGIS2.18<br>
landbouwschadesjabloon:  <br>
In shape formaat  te downloaden. Een voorbeeld van Tongeren. Geschikte attributentabel. Percelenkaart van je gemeente ( adp van grb). https://download.vlaanderen.be/ <br>

Voor het maken van keuze tabellen verwijs ik naar https://docs.qgis.org/2.8/en/docs/training_manual/create_vector_data/forms.html<br>

landbouwgebruikersperceel: ( eventueel)<br>
Bundeling van de datasets die een overzicht geven van de percelen die in landbouwgebruik zijn op de uiterste indieningsdatum van de verzamelaanvraag van een bepaald jaar. (download shape via https://download.agiv.be/Catalogus)<br>

potentiële bodemerosiekaart: ( eventueel)<br>
De potentiële bodemerosiekaart per perceel (2018) geeft aan de hand van een klasse-indeling de totale potentiële erosie van een bepaald landbouwperceel weer. >  WFS https://www.dov.vlaanderen.be/geoserver/wfs?<br>

Orthofoto recent: <br>
WMS die de compilatie weergeeft van de meest recente orthofotowerkbestanden voor Vlaanderen |  wintervluchten https://geoservices.informatievlaanderen.be/raadpleegdiensten/OMWRGBMRVL/wms?<br>

Beelden van de satelliet sentinel2: ( eventueel)<br>
aardobservatiebeelden tijdstip van ‘ramp’ <br>
Copernicus Services Data Hub > https://cophub.copernicus.eu/dhus/#/home <br>

SATELLIETBEELDEN BEREKENEN: ( eventueel)<br>
Als hulpmiddel bij het verwerken van landbouwschade willen we via satellietbeelden berekenen hoeveel schade ( verlies aan chlorofyl) er aan het gewas is.
Volg de stappen in de PDF satellietbeelden rekenmodel: model, pythonscript en layersetting kan je mee downloaden

PROJECT ROUTE IN QGIS 3.4<br>
lagen: <br>
de ingevulde landbouwschade-sjabloon<br>
wegenregister (WVB wegverbinding) van je gemeente > https://download.vlaanderen.be/ <br>

model: <br>
QGIS3-LB.model3  voor het berekenen van de geschikte route <br>

QFIELD (FOSS)<br>
QFieldSync plugin: <br>
Via de QFieldSync plugin in QGIS worden de data voorbereid.<br>
Download: https://plugins.qgis.org/plugins/qfieldsync/ <br>
Uitleg: http://www.qfield.org/docs/nl/<br>

filmpjes implementatie: <br>
kort: https://www.youtube.com/watch?v=cneYK3Y5ees<br>
uitgebreid: https://www.youtube.com/watch?v=rX3oyTCygew<br>
Via een usb-stick kunnen ze gevisualiseerd worden.<br>

QField for QGIS <br>
Op een tablet kan de QField-app worden gedownload > https://play.google.com/store/apps/details?id=ch.opengis.qfield&hl=nl<br>

Systeem tablet: Android, liefst met data-abonnement zodat er onderweg mogelijkheid is tot ontvangst.<br>

ARCMAP | ARCGISONLINE (BETALEND)<br>
De landbouwschade.gdb bevat een  een feature class en de toolbox met het landbouwmodel.<br>

COLLECTOR<br>
Op een tablet kan de Collector-app van Arcgis worden gedownload. Systeem tablet: apple of android, liefst met data-abonnement zodat er onderweg mogelijkheid is tot ontvangst. Er kan een foto aan een dossier toegevoegd worden onderweg.>
 https://play.google.com/store/apps/details?id=com.esri.arcgis.collector

DOWNLOAD DATA<br>
Na het verzamelen van de dat op terrain, kan je een csv-file downloaden als je met arcgisonline werkt of de database via aan stick binnenhalen bij Qfield.<br>

KOPPELING  COMPENSATIE<br>
Je vindt in de map ook een exceltabel terug waarin je je gecollecteerde data kan koppelen.<br>

Met dank aan de vele medewerkers van QGIS en QFIELD<br>
QGIS ontwikkelingsinspanningen: https://www.openhub.net/p/qgis<br>
Ontwikkelaars https://www.openhub.net/p/qgis/contributors?sort=latest_commit<br>
Behalve de ontwikkelaars zijn er vele anderen betrokken bij het project QGIS. https://qgis.org/en/site/getinvolved/governance/governance.html<br>
http://www.opengis.ch/about/<br>

