# Skillyr Learn · M02 Testversion

Eigenständige, inoffizielle Lern-App zum Thema **M02 – Planen von Softwarearchitekturen**.

## Verwenden

Die App besteht vollständig aus `index.html`: herunterladen und im Browser öffnen oder die GitHub-Pages-Testseite nutzen:

https://tomhe1609.github.io/skillyr-m02-test/

Die Website benötigt zum Laden eine Internetverbindung. Ein heruntergeladenes Exemplar funktioniert auch ohne Netz. Es sind keine Installation, Bibliotheken, externen Schriftarten oder API-Schlüssel erforderlich.

## Inhalt und Funktionen

- Vier Lektionen mit 24 neu formulierten Aufgaben (16 Multiple Choice, 8 Freitext).
- Themen: Anforderungen und Qualitätsziele, Bausteine und Architekturstile, Schnittstellen und Daten, Entscheidungen und Risiken.
- Gemischte Runden, gezielte Übungsmodi, Wiederholung und gemerkte Aufgaben.
- Multiple Choice: Vergleich mit der hinterlegten Lösung und Erklärung.
- Freitext: Musterlösung und Kriterien, anschließend bewusste Selbsteinschätzung. Teilweise verstanden zählt als ein halber Punkt.
- Lokal gespeicherter Fortschritt, laufende Runde und Antwortentwurf; Export und Import als JSON-Datei.
- Nutzbar auch ohne dauerhaften Browserspeicher; in diesem Fall weist die App auf die Sicherung per Export hin.

**Echte KI ist nicht angebunden.** Es gibt keine automatische KI-Bewertung und keine Anfragen an einen KI-Dienst. Für eine spätere KI-Anbindung wäre ein geeigneter Backend-Dienst erforderlich; geheime Schlüssel gehören nicht in Browser-Code.

## Daten und Abgrenzung

Die App überträgt keine Lernantworten oder Fortschrittsdaten an einen Server. Sie verwendet ausschließlich den lokalen Speicherschlüssel `skillyr-learn-m02-test:v1`. Ein anderer Browser, ein anderes Gerät und ein lokal geöffnetes Exemplar haben getrennte Lernstände. Der Hosting-Anbieter verarbeitet beim Seitenaufruf die üblichen technischen Verbindungsdaten.

Keine offizielle Skillyr-App und keine Verbindung zum Skillyr-Konto. Die App enthält keine übernommenen Skillyr-Lernkarten, Kursfolien oder Markenbilder. Alle Fragen und Musterlösungen wurden für diese allgemeine Übung neu formuliert. Es sind keine offiziellen Prüfungsfragen und kein vollständiger Lehrplan.

Das separate Repository `TomHe1609/It-lernquiz` wird von dieser App und ihrer Veröffentlichung nicht verändert. Es wird kein Service Worker registriert.

## Veröffentlichung

GitHub Pages: **Deploy from a branch → main → /(root)**. Der einzige App-Einstiegspunkt ist `index.html`; `.nojekyll` deaktiviert die nicht benötigte Jekyll-Verarbeitung.

## Geprüft

- Desktop und mobile Ansichten bei 320, 375, 390, 768 und 1440 Pixeln ohne seitlichen Überlauf.
- Richtige und falsche Auswahlantworten; Musterlösungen und Selbsteinschätzung.
- Speicherung und Wiederaufnahme nach Neuladen ohne doppelte Wertung.
- Wiederholung, Markierungen, Sicherungsexport und gültiger/ungültiger Import.
- Betrieb mit gesperrtem Browserspeicher und lokal ohne Netzwerk.
- Keine ausgehenden Anfragen des App-Codes, keine externen Abhängigkeiten und keine gefundenen Schlüssel-Muster.
