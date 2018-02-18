# EidI Übung Zusammenfassung
## Übungsblatt 1
### Laufzeitberechnung

## Blatt 2
### Boolsche Ausdrücke

## Blatt 3
### Präzedenzregeln
### `char` handling
### Modulo Operator

## Blatt 4
### Schleifen
### Zufallszahlen

## Blatt 5
### Arrays

## Blatt 6
### Überdeckung, Variablen

## Blatt 7
### O-Notation
### Parameterübergabemechanismen
### Rekursion

## Blatt 8
### Head-, Tailrekursion

## Blatt 9
### Lineare, Binäre Suche
#### Lineare Suche
Iterieren über die gesamte Datenmenge bis das gewümschte Element gefunden wurde
#### Binäre Suche
Bei sortierten Datenmengen kann der Suchbereich schnell eingeschränkt werden, da der Suchbereich durch Vergleich mit dem mittleren Element bei jeder Iteration halbiert wird.
### Divide and Conquer
Prinzip des Aufteilens eines Problems in viele kleinere Teilprobleme ("divide") und späteres Zusammenfügen der Lösungen zu einer Gesamtlösung ("conquer")
### Sortieralgorithmen: Bubble-, Shaker-, Insertion-, Selectionsort
#### Bubblesort
Tauschen eines Elements mit dem nachfolgendem, sodass diese beiden Elemente in richtiger Reihenfolge stehen.
Dies wird über die Ganze Liste ausgeführt und dann wiederholt bis die Menge sortiert ist.
Dies hat den Effekt dass in der ersten Iteration das größte Element "zum Ende der Liste aufsteigt" wie eine Luftblase, bei der Zweiten Iteration das Zweitgrößte und so weiter.
Laufzeit: O(n)-O(n²)
#### Shakersort
Abwechselndes Ausführen von Bubblesort in alternierende Richtungen
#### Insertionsort
In jeder Iteration wird das erste unsortierte Element an der richtigen Stelle im sortierten Bereich eingefügt.
Das entspricht dem manuellen Sortieren von Spielkarten bei enem Kartenspiel.
#### Selectionsort
In jeder Iteration wird das kleinste unsortierte Element gewählt und an das Ende des sortierten Bereichs getauscht.

## Blatt 10
### Sortieralgorithmen: Quick-, Heap-, Mergesort
### Stabilität, Laufzeit von Sortieralgorithmen
### Backtracking

## Blatt 11
### OOP: Konstruktion von Klassenstrukturen

## Blatt 12
### OOP: Sichtbarkeit, Klassenstruktur
#### Sichtbarkeit
* `public`
    * Zugriff von überall möglich 
* `package`
    * Zugriff nur aus dem gleichen package möglich
* `protected`
    * Zugriff nur aus der eigenen Klasse und aus von der Klasse erbenden Unterklassen möglich
* `private`
    * Zugriff nur aus der eigenen Klasse möglich

## Blatt 13
### Single linked list
Jedes Element der Liste enthält neben den Daten einen Zeiger auf das jeweils nächste Element.
Die Liste besteht im Wesentlichen nur aus einem Zeiger auf das erste Element der Liste.
Es kann sinnvoll sein, auch die aktuelle Länge oder einen Zeiger auf das aktuell letzte Element zu speichern.
### Ringliste
Bei der Ringliste zeigt das "letzte" Element wieder auf das erste. Die Ringliste enthält daher nur einen Zeiger auf ein beliebiges Element der Liste.
### Doubly linked list
Die doubly linked list erweitert das Element aus der single linked list um einen Zeiger auf das jeweils vorherige Element.
### Binärbaum
Ein Node des Baumes zeigt auf maximal 2 Child-Nodes.

## Blatt 14
### Traversierungen von Bäumen
#### Pre Order
Reihenfolge: `this`, `left`, `right`
#### In Order
Reihenfolge: `left`, `this`, `right`
#### Post Order
Reihenfolge: `left`, `right`, `this`
### Suchbaum
Ein Sortierter Baum wird dadurch erzeugt, dass Elemente abhängig von einem Wert im Baum einsortiert werden. Beispiel: Das kleinere Element wird links einsortiert.
### OOP: Vererbung, Abstrakte Klassen
#### Vererbung
Klassen können von maximal einer anderen Klasse oder abstrakten Klasse erben. Dabei werden Parameter und Methoden übernommen. Zugriff auf `public` oder `protected` Member der Oberklasse möglich, Zugriff auf `private` Member nicht möglich.
#### Abstrakte Klasse
* Kann nicht instanziiert werden
#### Abstrakte Methode
* Definiert nur Signatur
* Muss in Unterklassen überschrieben werden

## Themen nach Blatt 14
### Interfaces
* Können wie Datentypen verwendet werden
* Können nicht instanziiert werden
* Vererbung wie bei Klassen Möglich
### UML

## Stuff der sonst so relevant erscheint aber anscheinend nicht in der Übung war
### Stack
### Queue
