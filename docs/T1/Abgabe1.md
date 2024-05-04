# T1-Abgabe1: Zielsetzung

## Grundgedanke
Meine erste Berührung mit der Formel 1 ist noch nicht lange her, als ich mit einem Freund in Monaco war. Ich war sehr erstaunt, wie klein eine Rennstrecke doch sein kann. Nach diesem Ereignis habe ich mich mehr mit dem Thema Formel 1 beschäftigt und schaue momentan ab und zu das Rennen.
Daher freute es mich, als ich nach einigem Googeln eine API gefunden habe, die genau dieses Thema unterstützt. Somit nutze ich nun diese API und baue dazu, wie mit Herrn Inauen schon besprochen, ein GUI auf.

## Beschreibung API
Meine API ist frei Nutzbar und aktualisiert sich ständig.

Die Abfragen sind schlicht und einfach hier ein paar Beispiele:

```markup
http://ergast.com/api/f1/drivers
```
Gibt alle Fahrer die in der Formel 1 gefahren sind aus

```markup
http://ergast.com/api/f1/2023/drivers.json
```

Gibt alle Fahrer der Saison 2023 als json file aus.
```markup
http://ergast.com/api/f1/drivers/max_verstappen
```
Gibt den Fahrer Max Verstappen aus

## Aufgabenstellung
Ich möchte eine Applikation bauen, die diese API nutzt. Dazu möchte ich eine elegante Lösung finden, um die JSON-Daten einfach darzustellen, damit man sie leicht lesen kann. Dies möchte ich zum Beispiel mit einem Dashboard für einen Fahrer umsetzen.
Als erstes werde ich mich an die Saison 2023 wagen, da dies die neueste vollständige Saison ist. Falls ich am Schluss noch Zeit habe, werde ich mich auch anderen Saisons zuwenden.

## Anforderungen
- Fahrer Abfragen
- Teams Abfragen
- Zeiten von einem bestimmten Fahrer abfragen
- Einfaches Dashboard mit sinnvoller Übersicht
