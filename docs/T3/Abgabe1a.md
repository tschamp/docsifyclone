# JUnit Testing ist in der Anwendung erläutert (wie starten, Ausgabe, wo programmiert)

## JUnit
JUnit ist ein Framework zum Testen von Java-Methoden. 
Es bietet eine Möglichkeit, die Funktionsfähigkeit von Klassen und Methoden zu überprüfen. 
Es stellt sicher, dass der Code korrekt funktioniert, so wie man es sich wünscht.

## Einrichten
In einem Maven-Projekt werden Imports, die nicht standardmässig von Java bereitgestellt werden, in der pom.xml hinzugefügt. 
Um JUnit im Projekt einzubinden, muss man folgenden Code in die pom.xml hinzufügen:

```xml
<dependency>
    <groupId>junit</groupId>
    <artifactId>junit</artifactId>
    <version>4.13.2</version>
    <scope>test</scope>
</dependency>
```

## Schreiben von Tests:
Tests werden geschrieben, um zu überprüfen, ob eine Methode funktioniert. 
Um einen Test zu kennzeichnen, verwendet man die Annotation @Test. 
Der Test muss eine assertEquals-Methode beinhalten, damit das Programm herausfinden kann, ob die Methode erfolgreich funktioniert hat oder nicht.

## Ausführen des Tests:
Die Tests starte ich mit den grünen Pfeilen links neben den Methoden. 
Die Tests können entweder alle zusammen gestartet werden oder auch als einzelne Methode:
![Test Image](/Pictures/how-to-start-test.png)

## Analyse der Ausgabe
Die Ausgabe zeigt, ob der Test erfolgreich war oder nicht. 
Dies sieht dann so aus:
![Example Image](/Pictures/how-to-see-if-test-is-good.png)

In diesem Fall wurden alle Tests erfolgreich durchgeführt.