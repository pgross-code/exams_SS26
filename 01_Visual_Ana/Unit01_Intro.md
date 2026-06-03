# 01 - 01: Introduction into Data Mining

## Frequent pattern mining

Hierbei geht es häufig darum auftretende Muster oder Zusammenhänge in einem Datensatz zu identifizieren. Dies geschieht durch die Analyse großer Datensätze, um Elemente oder Gruppen von Elementen zu finden, die häufig gemeinsam vorkommen.

- e.g.: many customers of a supermarket buy beer and potato chips (crisps) (“market basket analysis")

Dieses Verfahren kann wertvolle Einblicke in die Zusammenhänge und Beziehungen zwischen verschiedenen Komponenten oder Merkmalen innerhalb der Daten liefern.

### Mögliche Anwendungen:

- Verbesserung der Produktanordnung in Regalen
- Unterstützung von Cross-Selling (Vorschläge für weitere Produkte)
- Fehlererkennung (z. B. wenn ein bestimmtes Ereignis eintrat, wurde es von einer Maschine überwacht)

Muster können als Assoziationsregeln ausgedrückt werden:

`IF a customer buys beer THEN she/he will probably also buy potato chips with a probability of X`

## Association rule mining :

Quelle: https://www.datacamp.com/tutorial/association-rule-mining-python

Das Ziel der Assoziationsregelanalyse ist es, Regeln aufzudecken, die die Beziehungen zwischen verschiedenen Elementen im Datensatz beschreiben.
