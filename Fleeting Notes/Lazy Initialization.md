
--- 
Erstellt: 2024-03-22    14:12 
Tags: #inProcess #PHP 
Link Up: [[PHP]]
Link Down:

--- 
# Definition
Lazy Initialization ist ein Design Pattern, bei dem die Initialisierung eines Objekts erst dann erfolgt, wenn es tatsächlich benötigt wird, und nicht im Voraus. Dieses Konzept zielt darauf ab, die Einfachheit der Verwendung zu bewahren und die Leistung zu verbessern.

# Was macht das Lazy Initialization Pattern
- Bei der Lazy Initialization wird die Erstellung eines Objekts so lange wie möglich hinausgezögert
- Statt ein Objekt sofort zu erstellen, wird es erst dann erzeugt, wenn es **wirklich benötigt wird**
- Ein häufiges Beispiel ist die späte Erstellung einer Datenbankverbindung, die nur dann erfolgt, wenn tatsächlich Daten aus der Database abgerufen werden müssen
## References
1. [[Design Pattern]]

## Quellen
1. https://stackoverflow.com/questions/978759/what-is-lazy-initialization-and-why-is-it-useful