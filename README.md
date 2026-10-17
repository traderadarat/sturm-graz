# Nicht die Stadt fördert Sturm. Sturm fördert die Stadt.

Faktenanalyse zum wirtschaftlichen, gesellschaftlichen und internationalen Wert des SK Sturm Graz für die Stadt Graz: Werbewert, Wertschöpfung, Steuern, Stadionfrage, soziales Engagement von Verein und Fans.

Text und Recherche: Günter Kohlhofer, Graz. Erstveröffentlichung 16. Oktober 2026, zuletzt aktualisiert 17. Oktober 2026.

## Aufbau

Eine einzelne Seite (`index.html`) mit eingebettetem CSS und einem kleinen eigenen Skript. Die Grafiken bestehen aus reinem HTML und CSS. Änderungen am Text direkt in `index.html` vornehmen und die Seite neu veröffentlichen.

## Änderungen pflegen

Bei jeder inhaltlichen Änderung an drei Stellen nachziehen:

1. Randnotiz „Zuletzt aktualisiert“ ganz unten in `index.html`: Datum und ein kurzer Eintrag
2. Kopf von `index.html`: `dateModified` im JSON-LD und `article:modified_time`
3. `sitemap.xml`: `lastmod`

Reine Gestaltungs- oder Technikänderungen kommen nicht ins Änderungsprotokoll.

## Suchmaschinen

- `sitemap.xml` und `robots.txt` liegen im Hauptordner.
- Strukturierte Artikel-Daten (schema.org, JSON-LD) stehen im Kopf von `index.html`: Titel, Beschreibung, Bilder, Datum der Erstveröffentlichung und der letzten Änderung, Autor.

## Datenschutz

- Keine Cookies, keine Tracker, keine eingebetteten Inhalte Dritter.
- Schriften werden lokal aus dem Ordner `fonts/` geladen, es gehen keine Anfragen an Google oder andere Schriftanbieter.
- Links zu den Quellen führen erst beim Anklicken zu den jeweiligen Webseiten.
- GitHub Pages protokolliert laut eigener Dokumentation die IP-Adressen der Besucher.
- Die Seite darf von Suchmaschinen aufgenommen werden (kein noindex).
- Die Teilen-Buttons sind einfache Links ohne eingebettete Skripte von Facebook, WhatsApp und Co. Eine Verbindung zum jeweiligen Dienst entsteht erst beim Anklicken.
- Ein kleines eigenes Skript in `index.html` steuert „Link kopieren“, die Lesefortschrittsleiste, den Nach-oben-Knopf, die Quellen-Vorschau beim Darüberfahren oder Antippen der Quellenzahlen und das verschiebbare Inhaltsverzeichnis. Dessen Position und ob es offen ist, merkt sich nur der Browser des Besuchers (localStorage); es wird nichts übertragen.
- `og-image.png` ist das Vorschaubild, das Facebook und Messenger beim Teilen anzeigen.

## Quellen

Alle Zahlen sind im Text nummeriert belegt, das vollständige Quellenverzeichnis (123 Einträge) steht am Ende der Seite. Abrufstand: 17. Oktober 2026.

## Schriftlizenzen

- Big Shoulders Display, SIL Open Font License 1.1 (`fonts/OFL-bigshouldersdisplay.txt`)
- Source Serif 4, SIL Open Font License 1.1 (`fonts/OFL-sourceserif4.txt`)

## Bildnachweise (Ordner `images/`)

Die Fotos wurden verkleinert, ohne Kameradaten als WebP gespeichert und teils als Ausschnitt gezeigt.

- `uhrturm-abend.webp`: Laszlo Biro, https://unsplash.com/photos/a-clock-tower-in-the-middle-of-a-city-at-night-tVwOW-Ikklc, Unsplash-Lizenz
- `sturm-fahne.webp`: jorono, Pixabay (Nr. 3566647), Pixabay-Inhaltslizenz
- `liebenau-abend.webp` und `schal-klagenfurt.webp`: eigene Fotos von Günter Kohlhofer

## Offenlegung

Offenlegung nach § 25 Mediengesetz und Datenschutzhinweise stehen am Ende der Seite (Abschnitt „Offenlegung und Datenschutz“).

## Adresse

Die Seite ist unter https://sturm-fakten.at/ erreichbar (Domain bei easyname, DNS auf GitHub Pages).
