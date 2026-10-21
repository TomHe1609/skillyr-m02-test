# Skillyr Learn – öffentliche Testversion M01 bis M05

Testseite: https://tomhe1609.github.io/skillyr-m02-test/

Die vorhandene Pages-App wurde im gleichen dunklen Lernpfad-Stil um M01, M03, M04 und M05 erweitert. Das Repository bleibt absichtlich unter seiner bisherigen Adresse erreichbar.

## Umfang

| Modul | Themen | Lektionen | Multiple Choice | Freitext | Trainingskarten |
|---|---|---:|---:|---:|---:|
| M01 | Lern- und Arbeitsmethodik | 3 | 9 | 3 | 9 |
| M02 | Analysieren und Planen der Softwarearchitektur | 13 | 49 | 13 | 49 |
| M03 | Entwickeln von Softwarearchitekturen | 11 | 33 | 11 | 33 |
| M04 | Sicherstellen der Produktqualität | 6 | 18 | 6 | 18 |
| M05 | Software- und Anwenderdokumentation | 6 | 18 | 6 | 18 |

Insgesamt 39 Lektionen, 127 Multiple-Choice-Fragen, 39 Freitextaufgaben und 127 Trainingskarten. M06–M09 sind im aufklappbaren Hinweisbereich sichtbar, aber noch nicht aktiv.

M01 und M03 folgen den bereits vorliegenden Kurslektionen. M04 und M05 lagen als größere Themenblöcke vor und wurden für diese Testversion jeweils in sechs kompakte Trainingsabschnitte gegliedert. Das ist ein Übungsstand und kein vollständiger Ersatz des Kurses. M02-Inhalte und Aufgabenkennungen bleiben erhalten.

## Oberfläche

Die Startseite bündelt Modulauswahl, Lernstand und eine schlanke geschwungene Timeline mit versetzten Stationen. Einheitliche SVG-Linienicons ersetzen die farbigen Symbole in der Kopf- und Fußnavigation. Hinweise und künftige Module stehen im aufklappbaren Bereich „Über diese Testversion“.

## Lernen

- Erklärungen und Beispiele vor dem gemischten Quiz.
- Freitext mit Musterlösung und bewusster Selbsteinschätzung; echte KI bleibt deaktiviert.
- XP für erstmals richtig gelöste Aufgaben, lokaler Lernstand und Lerntage.
- Eigener Lernpfad und Kartenfilter pro Modul, gemeinsame Fortschrittsübersicht.
- Fehlertraining pro Modul oder über alle fünf Module.
- Export/Import des gesamten Lernstands und Offline-Unterstützung nach dem ersten erfolgreichen Laden.

## Bisherigen M02-Fortschritt erhalten

Die neue App verwendet `skillyr_learn_m01_m05_preview_v1`. Beim ersten Start wird ein gültiger bisheriger Stand aus `skillyr_learn_m02_preview_v1` automatisch übernommen. Der alte Eintrag wird dabei weder geändert noch gelöscht. Ein vorhandener neuer Lernstand wird nicht überschrieben.

Neue Exporte tragen die App-Kennung `skillyr-learn-m01-m05`; bisherige M02-Exporte mit `skillyr-learn-m02` werden ebenfalls angenommen. Ein Import ersetzt nach ausdrücklicher Bestätigung den ganzen aktuellen Lernstand. Die Sicherung kann eigene Freitexte enthalten. Andere Browser oder Geräte haben getrennte Lernstände.

## Quellen und Grenzen

Grundlage sind die bereits vorliegenden Kursthemen, die öffentliche M02-Paketfassung und die zuvor neu formulierten Übungsfragen. Zusätzliche Erklärungen und Übungen für M04/M05 wurden eigenständig erstellt. Originale Lernkarten, Kursfolien, private Entwicklungsdateien und API-Schlüssel sind nicht Teil dieser Veröffentlichung. Es handelt sich um ein eigenständiges, inoffizielles Lernangebot und keine offiziellen Prüfungsfragen.

Die App führt keine KI-Aufrufe aus und enthält keine aktivierbare KI-Verbindung. Eine spätere Anbindung setzt einen geeigneten sicheren Server voraus. Die App sendet keine Lernantworten an einen Server; beim Seitenaufruf fallen die üblichen Verbindungsdaten des Hosting-Anbieters an.

## Veröffentlichung und Isolation

GitHub Pages: `main` und `/(root)` im Repository `TomHe1609/skillyr-m02-test`.

`index.html` enthält die eingebetteten App-Daten; `data-m01-m05.json` stellt denselben öffentlichen Inhalt separat bereit. Die bisherige `data-m02.json` bleibt unverändert als Kompatibilitätsdatei erhalten. Der Service Worker speichert nur Dateien dieser Test-App und entfernt ausschließlich ältere Caches mit dem Präfix `skillyr-m02-test::`.

`TomHe1609/It-lernquiz`, dessen Pages-Konfiguration, lokale Speicher und Offline-Caches werden nicht verändert.
