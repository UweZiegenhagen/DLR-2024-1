# DLR-2024-1

Öffentliche Materialien für den Einführungskurs 2024 LaTeX am DLR

## Kurstermine

* Dienstag, 2024-06-04
* Donnerstag, 2024-06-06
* Dienstag, 2024-06-11
* Dienstag, 2024-06-18

An jedem Tag treffen wir uns von 9--11 und 13--15 im virtuellen Kursraum, die Zugangsdaten werden per E-Mail versandt.

## Wie kommt man an die Materialien?

git installieren und dann auf der Kommandozeile

git clone https://github.com/UweZiegenhagen/DLR-2024-1.git

Updates holt man wie folgt, lokal geänderte Dateien werden dabei überschrieben!

git fetch --all
git reset --hard origin/main

In den nächsten Wochen und Monaten wird das Repository noch öffentlich zugänglich sein, 
irgendwann werde ich es auf privat setzen. Ihr könnt es gern forken, aber dann
bitte in ein privates Repository, da ich gern Wildwuchs verhindern möchte.


## Was wird benötigt

* Ein Rechner (Laptop, Desktop) mit Windows, MacOS oder Linux
* TeX Live 2024 herunterladen und installieren von tug.org/texlive. Eine Anleitung (für TeX Live 2022, es hat sich aber nichts wesentliches geändert) habe ich unter https://www.youtube.com/watch?v=k9KhuZz7k-Q veröffentlicht.
* Wenn ihr unter Linux arbeitet: Bitte nicht aus den Distributionsquellen nehmen, sondern auch von tug.org installieren. Das TeX Live in den Distributionen ist oftmals nicht aktuell. 
* Mac-User installieren bitte MacTeX (auch auf der tug.org Seite frei verfügbar)
* Ein Editor zur Bearbeitung der TeX-Dateien: TeX Live bringt für Mac und Windows TeXworks mit, einen guten und einfach zu bedienenden Editor, den ich persönlich gern benutze.
* Grundkenntnisse von Git bzw. Github sind nicht verkehrt, da alle meine Dateien im Github liegen.

## Kursinhalte

Die Kursinhalte sind flexibel und orientieren sich am Bedarf und Tempo der Teilnehmerinnen und Teilnehmer, mit dem folgenden Ablauf plane ich:

### Tag 1 - Grundlagen

* Vorstellung der Beteiligten, wer bin ich und wer seid ihr, was sind eure Lernziele? ✓
* Gibt es Vorlagen, die ihr nutzen müsst oder wollt? ✓
* Historie von TeX und LaTeX ✓
* Check der Umgebungen bzw. Installationen mittels "Hallo \LaTeX" Dokument ✓
* Klassen, Pakete, Umgebungen und Befehle ✓
* Schneller TeX mit Autohotkey & Co ✓
* Warum man article, report und book nicht unbedingt nutzen sollte -- die KOMA-Klassen ✓
* Strukturierte Dokumente, ``\chapter``, ``\section`` & Co, Inhaltverzeichnisse ✓
* Referenzen mit ``\label`` und ``\ref``, prettyref ✓
* Einfache Bilder einbetten, Bilderverzeichnisse ✓
* Einfacher Tabellensatz und Tabellenverzeichnisse ✓
* Einzelne Seiten drehen im PDF mit dem ``pdflscape`` Paket ✓
* Float-Objekte bei Tabellen und Bildern ✓

### Tag 2 - Tabellen, Mathematik, und mehr

* Wiederholung vom 1. Tag, Fragen beantworten ✓
* Tabellensatz mit multicolumn und multirow ✓
* LaTeX automatisieren mit ``Arara`` ✓
* Einheitensatz mit ``siunitx`` ✓
* Mathematiksatz (ohne und mit ``amsmath``) ✓
* Präsentationen mit ``Beamer`` ✓
* Briefe setzen mit ``scrlttr2`` ✓
* Poster erstellen mit LaTeX
* Lebensläufe erstellen mit LaTeX ✓
* Quellcode-Listings einfügen mit dem ``Listings`` Paket
* Wir bauen eine Vorlage für Seminar- und Abschlussarbeiten: ``titlepage``


### Tag 3 - Bibliografien und Präsentationen

* Zusammenfassung vom 2. Termin, Wiederholung
* Flyer basteln mit ``leaflet``
* Seitenränder einstellen mit ``geometry``
* Kopf/Fußzeilen anpassen mit ``scrpage``
* Mehr zum Bilder einbetten: ``subcaption`` 
* Fonts für ``pdflatex``, der LaTeX Font Katalog (https://tug.org/FontCatalogue/)
* Von ``pdflatex`` zu ``lualatex``, Systemschriften nutzen
* Einfache Bibliografien -- die ``thebibliography`` Umgebung
* Bitte Jabref von www.jabref.org installieren, kostet nichts und ist sehr gut. Alternativ kann man die entsprechenden Dateien auch mit dem Texteditor bearbeiten.
* Komplexe Bibliografien mit ``biblatex``, ``biber`` und ``jabref``

### Tag 4 - TikZ und Sonstiges

* Fragen zum letzten Mal?
* Brief-Design anpassen
* Kopf/Fußzeilen anpassen mit ``scrpage``
* Mehrere Schriftarten im Dokument
* Grafiken erstellen mit LaTeX-Paketen, kurze Einführung in ``TikZ``
* Umrahmte (farbige) Boxen mit ``tcolorbox`` (``texdoc tcolorbox``), alternativ siehe das ``mdframed`` Paket
* Syntaxhighlighting mit pygments
* Editoren: ``TeXworks`` versus ``Visual Studio Code`` 
* Frage-und-Antwort-Teil: was fehlt euch noch, was wolltet ihr schon immer mal TeXen?

## Literaturempfehlungen

Empfohlen werden:

* Alle Bücher von Herbert Voß (https://www.lehmanns.de/search/quick?PHPSESSID=mi28bh61dhv2nu8keg4hjnkunumgi5ah&mediatype_id=&q=herbert+vo%C3%9F), insbesondere die Einführung
* Der LaTeX Companion in der 3. Auflage, wenn man mehr wissen möchte

