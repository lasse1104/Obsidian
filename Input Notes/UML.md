
--- 
Erstellt: 2025-02-27    09:45 
Tags: 
Link Up: 
Link Down:

--- 
# UML-Diagramme

#### Klassendiagramm
Beliebt in UML ist beispielsweise das Klassendiagramm. Klassendiagramme werden zum Beispiel häufig von Software-Ingenieuren genutzt, um die Software-Architektur zu dokumentieren.
Die Idee hinter UML war es, ein normiertes Modell zur Beschreibung eines objektorientierten Codierungsansatzes zu entwickeln. Da Klassen die Bausteine von Objekten darstellen, können Klassendiagramme als die Bausteine von UML verstanden werden.
###### Zugriffsmodifikatoren
- Öffentlich (+)
- Privat (-)
- Geschützt (#)
- Paket (~)
- Abgeleitet (/)
- Statisch (unterstrichen)
### Aufbau
1. Name
2. Attribute
	1. Attributname : Datentyp = (Initialisierung)
3. Methoden
	1. Methodenname(Parameter: Datentyp): Rückgabewert
###### Vererbung
Die Unterklasse erhält alle Eigenschaften und Methoden der Oberklasse (Dargestellt durch eine geschlossenen Pfeilspitze)
![[Pasted image 20250227125559.png]]
In diesem Beispiel würde das Objekt „Auto“ (Car) alle Attribute 
(Geschwindigkeit, Mitfahrerzahl, Treibstoff) und Methoden (Los(), Stop(), Richtungswechsel()) der Parent-Klasse „Fahrzeug“ (Vehicle) annehmen. 
Hinzu kämen spezifische Attribute (Modelltyp, Türenzahl, Autohersteller) und Methoden (Radio(), Scheibenwischer(), Klimaanlage/Heizung()) der eigenen Klasse.

#### Anwendungsfalldiagramm 
Ein UML Use-Case Diagramm(Anwendungsfalldiagramm) dient zur Veranschaulichung der unterschiedlichen Interaktionsmöglichkeiten zwischen einem Benutzer und einem System

**Aufgabe:**
![[Pasted image 20250226095554.png]]

### Lösung
![[Pasted image 20250226095623.png]]

#### Aktivitätsdiagramm
Mit Aktivitätsdiagrammen (Activity diagrams) können **zeitliche Abläufe** beschrieben werden. Damit ist es möglich Prozesse, Workflows und Algorithmen auf verschiedenen Abstraktionsniveaus zu beschreiben.
- **Aktivität:** Die Aktivität beschreibt die Ablaufreihenfolge von Aktionen. Sie wird durch ein Rechteck mit abgerundeten Ecken dargestellt
- **Entscheidungsknoten:** Eine an eine Bedingung geknüpfte Verzweigung im Fluss, die in Form eines Diamanten dargestellt wird. Entscheidungsknoten umfassen einen einzigen Input und zwei oder mehr Outputs
- **Kontrollflüsse:** Hierbei handelt es sich um eine andere Bezeichnung für Konnektoren, die den Fluss zwischen Schritten im Diagramm anzeigen.
- **Startknoten:** Symbolisiert den Beginn der Aktivität. Der Startknoten wird mit einem schwarzen Kreis dargestellt.
- **Endknoten:** Stellt den finalen Schritt in der Aktivität dar. Der Endknoten wird von einem umrandeten schwarzen Kreis symbolisiert.
![[Pasted image 20250306125106.png]]

## References

## References
1. 
