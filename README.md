# Calculator

## In diesem Projekt soll eine Taschenrechner-Funktion erstellt werden.

### Methode

Mit dem Aufruf **`Calculator.calculate(String toCalculate)`** soll ein mathematischer Ausdruck in Form eines Strings ausgewertet werden.

### Ausführung

Dazu muss dieser zunächst validiert und geparst werden. Im Anschluss wird der Ausdruck ausgewertet und dann als `Double` zurückgegeben.

### Exception

Sollte die Eingabe aus irgendeinem Grund nicht ausgewertet werden - z.B. weil der eingegebene oder auszugebende Zahlenbereich außerhalb des Wertebereichs von `Double` liegt, die Eingabe Syntaxfehler oder unzulässige Zeichen enthält etc. - soll `Null` zurückgegeben werden und eine `Exception` geworfen werden mit einer genauen Angabe des Fehlers.


## Umsetzung

Das Projekt wird als [Spring Boot](https://spring.io/projects/spring-boot) Applikation nur mit [Lombok](https://www.projectlombok.org/) initialisiert. Die Applikation soll gut wartbar/erweiterbar sein und zukünftig möglicherweise über einen Controller angesprochen werden können etc. Auch weitere Funktionen wie z.B. die Umrechnung von Fahrenheit in Celsius oder von US-Dollar in Euro etc. könnten implementiert werden.

Folgende mathematischen Operationen sollen von der Funktion ausgewertet werden:

- **+** : addieren
- **-** : subtrahieren
- <b>*</b> : multiplizieren
- **/** : dividieren
- **^** : potenzieren
- **!** : Fakultät
- **()** : Klammern
- -**-** : Vorzeichen

### Das komplette Projekt soll mit TDD umgesetzt werden.

-  als Übung, testgetrieben ein komplettes Projekt umzusetzen
- als Vergleich, mit der Umsetzung bei der binaris-informatik GmbH (mit Jörn)

Repository auf [GitHub](https://github.com/Gecko-develop/calculator).



------

###### Alles was hier entwickelt wird soll Spaß machen und in meiner Freizeit programmiert werden!

------
