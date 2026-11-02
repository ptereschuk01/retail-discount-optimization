# Projektbeschreibung

## Rabatt- und Ergebnisanalyse im Einzelhandel

Das Projekt untersucht den Zusammenhang zwischen Rabattstufen, Absatzmenge und Rohertrag. Ein Python-Notebook erzeugt synthetische Verkaufsdaten auf Basis festgelegter Produkt-, Preis- und Nachfrageannahmen. Ein Excel-Dashboard stellt die Ergebnisse für den Vergleich einzelner Produktszenarien bereit.

### Fachliche Fragestellung

Eine Absatzsteigerung führt nicht automatisch zu einem höheren Ergebnis. Ein Preisnachlass verringert den Ertrag je Einheit; zusätzliche Verkäufe müssen diesen Effekt ausgleichen. Die Analyse macht diesen Zusammenhang anhand verschiedener Rabattstufen sichtbar.

### Umsetzung

- Produktszenarien mit Einkaufskosten, Verkaufspreisen und angenommenen Nachfrageverläufen definieren.
- Verkaufsdaten mit Python, pandas und NumPy erzeugen.
- Rabattierten Preis und Rohertrag berechnen.
- Ergebnisse nach Produkt und Rabattstufe aggregieren und visualisieren.
- Kennzahlen in Excel über Pivot-Auswertungen und ein Dashboard zugänglich machen.

Der Ergebnisbeitrag wird als `(rabattierter Preis − Einkaufskosten) × Absatzmenge` berechnet. Weitere betriebliche Kosten sind darin nicht enthalten.

### Ergebnis und Anwendungsgrenzen

Das Ergebnis ist eine nachvollziehbare Szenarioanalyse mit interaktiver Auswertung. Die dargestellten Nachfrageeffekte folgen den gesetzten Annahmen; sie wurden nicht aus realen Handelstransaktionen geschätzt. Händlernamen im Notebook dienen ausschließlich als Simulationsbezeichnungen.

Für einen Einsatz zur tatsächlichen Preissteuerung wären reale Daten, zusätzliche Kosten und eine gesonderte Validierung der Nachfrageeffekte notwendig.

[Dashboard und vollständige Dokumentation](README.md)
