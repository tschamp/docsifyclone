# JUnit Beispiel (eigenes Beispiel) ist umgesetzt, angemessen ausführlich und lauffähig

In den folgenden beispielen wird zuerst der code gezeigt danach darunter die Notizen.


## Beispiel 1
```java
    @Test
    void testGetFamilyName() {
        Driver driver = new Driver();
        driver.setFamilyName("Smith");
        assertEquals("Smith", driver.getFamilyName());
    }
```

* In diesem Test wird überprüft, ob die Methode getFamilyName den richtigen Wert zurückgibt.
* Ein Driver-Objekt wird erstellt und der familyName auf "Smith" gesetzt.
* Der assertEquals-Aufruf vergleicht den erwarteten Wert "Smith" mit dem tatsächlichen Rückgabewert der getFamilyName-Methode.
* Der Test ist erfolgreich, wenn der Wert Smith zurückgegeben wird.

## Beispiel 2
```java
    @Test
    void testSetdateOfBirth() {
        Driver driver = new Driver();
        driver.setdateOfBirth("15-12-1985");
        assertEquals("15-12-1985", driver.getdateOfBirth());
    }
```
* Hier wird die Methode setdateOfBirth getestet, um sicherzustellen, dass sie das Geburtsdatum korrekt setzt.
* Ein Driver-Objekt wird erstellt und das Geburtsdatum auf "15-12-1985" gesetzt.
* Der Test überprüft mit assertEquals, ob die Methode getdateOfBirth den erwarteten Wert zurückgibt.
* Der Test ist erfolgreich, wenn der Wert 15-12-1985 zurückgegeben wird.


## Beispiel 3
```java
    @Test
    void testSetCountry() {
        Location location = new Location();
        location.setCountry("Deutschland");
        assertEquals("Deutschland", location.getCountry(), "Das Land sollte auf Deutschland eingestellt werden.");
    }
```

* Dieser Test überprüft die Methode setCountry der Klasse Location.
* Eine Location wird erstellt und das Land wird auf "Deutschland" gesetzt.
* Der assertEquals-Aufruf vergleicht den erwarteten Wert "Deutschland" mit dem tatsächlichen Rückgabewert der getCountry-Methode.
* Zusätzlich ist der dritte Parameter im assertEquals-Aufruf ist eine Fehlermeldung, die angezeigt wird, wenn der Test fehlschlägt.
* Der Test ist erfolgreich, wenn der Wert Deutschland zurückgegeben wird.


## Beispiel 4
```java
    @Test
    void testGetLng() {
        Location location = new Location();
        location.setLng("7.44744");
        assertEquals("7.44744", location.getLng(), "Der Längengrad sollte 7.44744 sein.");
    }
```

* In diesem Test wird die Methode getLng der Klasse Location überprüft.
* Eine Location wird erstellt und der Längengrad wird auf "7.44744" gesetzt.
* Der assertEquals-Aufruf vergleicht den erwarteten Wert "7.44744" mit dem tatsächlichen Rückgabewert der getLng-Methode.
* Zusätzlich ist der dritte Parameter im assertEquals-Aufruf ist eine Fehlermeldung, die angezeigt wird, wenn der Test fehlschlägt.
* Der Test ist erfolgreich, wenn der Wert 7.44744 zurückgegeben wird.