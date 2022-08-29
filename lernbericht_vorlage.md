# Lern-Bericht

Holzherr Janic Lern-Bericht

## Einleitung

Wir bearbeiteten das Modul 133. Im Modul 133 geht es um Webentwicklung mit JSF.

## Was habe ich gelernt?

Gelernt habe ich wie man eine Session erstellt und diese so nutzen kann um Daten für längere Zeit speichern kann.

## Beschreibung

Durch das verwenden von SessionScoped, kann man eine Session erstellen in der dann Daten über eine bestimmte Zeit gespeichert werden können.
Wichtig hier zu beachten ist, dass man implements Serializable verwendet. Ansonsten funktioniert die Session nicht.
```java
@SessionScoped
public class HelloController implements Serializable{
```
## Verifikation

Beim Code Snippet sieht man wie man eine Session inizialisiert. Das habe ich auch kommentiert. 

# Reflektion zum Arbeitsprozess

Es war für mich sehr leicht mich zu motivieren für das Modul zu arbeiten.
Was leider nicht so gut funktioniert hat, waren die Fehlermeldungen die aufgekommen sind während des Arbeitprozesses. Ich habe sehr viel den Lehrer gefragt anstelle von selber die Lösung zu finden.

**VBV**: Das nächste mal werde ich mehr versuchen die Fehlermeldungen selbst zu debuggen um ein verständnis für das Problem zu entwickeln.
