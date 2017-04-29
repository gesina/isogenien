# Vortrag zu Isogenien elliptischer Kurven

Dies ist die Ausarbeitung zu einem Vortrag über Isogenien, den Morphismen in der Kategorie der elliptischen Kurven.
Er wurde im Rahmen des Seminars [*Elliptic curves and the Weil conjectures*](http://www.mathematik.uni-regensburg.de/kerz/) im Sommersemester 2016 an der Universität Regensburg gehalten.
Die Hauptquelle ist *The arithmetic of elliptic curves* von J.H. Silverman.

## Kompilieren
Man benötigt `lualatex` aus der **TeXLive2016**-Distribution. Zum Kompilieren den folgenden Befehle ausführen

```bash
lualatex isogenien_ausarbeitung.tex
biber isogenien_ausarbeitung
lualatex isogenien_ausarbeitung.tex
```

## Dateiübersicht
- `isogenien_ausarbeitung.tex`: Hauptdatei mit Inhalt
- `isogenien_wdh.tex`: nötige Wiederholungen aus den vorherigen Vorträgen (ohne Beweise)
- `isogenien_literatur.bib`: Literatur


## Grobe Inhaltsübersicht
Wiederholung aus den vorherigen Vorträge (ohne Beweise):
- Kategorienantiäquivalenz zwischen der Kategorie der glatten Kurven und der Kategorie bestimmter transzendenter Körpererweiterungen
- Gruppenisomorphismus zwischen der 0ten Picardgruppe und der geometrischen Punktgruppe
- Addition/Subtraktion/Translation von Punkten sind Morphismen von Kurven
- Aussagen zum Verzweigungsindex:
  * Summenformel
  * Anzahl von Punkten im Urbild eines Punktes
- Hurwitz'sche Formel

Neue Definitionen/Aussagen:
- Definition Isogenie, Kategorie der Elliptischen Kurven
- Multiplikationsabbildung:
  * Definition
  * nicht konstant
  * Aussage über Torsionsfreiheit
  * Definition Torsions-Untergruppen
- Isogenien sind Gruppenhomomorphismen
- Eigenschaften von Isogenien als Homomorphismen:
  * Korrespondenz zwischen dem Kern einer Isogenie und der Automorphismengruppe Aut(K(E_1)/K(E_2)) der Körpererweiterungen
  * Äquivalent zum Homomorphiesatz für Elliptischen Kurven
  * Beweisskizze zur „Quotientenrechnung“ auf Elliptischen Kurven
