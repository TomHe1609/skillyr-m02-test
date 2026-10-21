# Skillyr Learn – öffentliche M02-Testversion

Öffentliche Testseite: https://tomhe1609.github.io/skillyr-m02-test/

Grundlage ist das bereitgestellte Paket `Skillyr_Learn_M02_Pages_Testbereit.zip`. Sein dunkler, spielerischer Lernpfad und die Lerninhalte wurden beibehalten.

## Enthalten

- M01–M09 als Modulübersicht, ausschließlich M02 aktiv.
- 13 Lektionen (2.0–2.12) mit Erklärungen und Praxisbeispielen vor dem Quiz.
- 49 selbst formulierte Multiple-Choice-Fragen, 13 Freitextaufgaben und 49 selbst formulierte Trainingskarten.
- Sofortiges Feedback, XP, Lerntage, Fehlertraining und persönlicher Lernbereich.
- Freitext mit Musterlösung und Selbsteinschätzung. Dies ist keine automatische KI-Bewertung.
- Lokaler Fortschritt sowie Export und geprüfter Import als JSON-Datei.
- Offline-Unterstützung nach dem ersten erfolgreichen Laden und Speichern durch den Browser; optional zum Home-Bildschirm hinzufügen.

## KI bleibt deaktiviert

Diese öffentliche Version enthält keinen aktivierbaren KI-Endpunkt und führt keine KI-Anfragen aus. Die Eingaben zur Serververbindung und die KI-Prüfschaltflächen wurden entfernt. Freitext und Musterlösungen bleiben vollständig nutzbar.

Eine echte Anbindung erfolgt erst nach Einrichtung eines sicheren Servers mit Nutzerzugang, Schutz vor Missbrauch, Kostenbegrenzungen und passenden Datenschutzhinweisen. Keine API-Schlüssel in Browser-Code oder Repository ablegen.

## Veröffentlichung und Trennung

GitHub Pages veröffentlicht ausschließlich dieses Repository über `main` und `/(root)`. Alle acht Dateien des öffentlichen Pakets liegen im Stammverzeichnis.

Das KI-v4-Entwicklungspaket und seine originalen Kurskarten sind nicht Teil dieser Veröffentlichung. Das öffentliche Übungsmaterial ist selbst formuliert, kein offizielles Angebot von Skillyr und keine Sammlung offizieller Prüfungsfragen.

Das Repository `TomHe1609/It-lernquiz` und dessen Pages-Einstellungen bleiben unverändert. Der Service Worker dieser Test-App ist auf ihren eigenen Pfad begrenzt und entfernt ausschließlich veraltete Caches mit dem Präfix `skillyr-m02-test::`. Zwischenspeicher anderer Apps werden nicht angefasst.

## Lokale Daten

Der Lernstand verwendet ausschließlich `skillyr_learn_m02_preview_v1` im lokalen Browserspeicher. Andere Geräte und Browser haben getrennte Lernstände; zum Übertragen dient der Export. Die Sicherung enthält gespeicherte Freitexte und sollte entsprechend behandelt werden. Die App sendet keine Lernantworten an einen Server; beim Seitenaufruf verarbeitet der Hosting-Anbieter die üblichen technischen Verbindungsdaten.

Bei gesperrtem Browserspeicher bleibt Lernen im Arbeitsspeicher möglich; ein sichtbarer Hinweis empfiehlt den Export. Ein Import mit ungültigem Format ersetzt den vorhandenen Lernstand nicht.
