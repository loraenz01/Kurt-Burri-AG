# Kurt Burri AG – Analyse der bestehenden Website und Konzept für den Neuaufbau

Analysierte Seite: https://kurt-burri.digitalone.site/ (Stand Oktober 2026)

## 1. Bestandsaufnahme

### Aufbau
Eine einzige Seite (One-Pager) mit fünf Blöcken:

1. Header: Logo, Links «Galerie» und «Kontakt», Telefonnummer, Button «Jetzt Termin vereinbaren» (führt zu local.ch)
2. Hero: Foto eines Kupferdachs mit dem Text «KURT BURRI AG»
3. «Über uns»: drei lange Aufzählungslisten (Sanitäre Installationen, Heizung, Spenglerei)
4. Galerie: 11 quadratische Vorschaubilder
5. Kontakt: Adresse, Telefon, Button «So finden Sie uns», Sprachwahl (nur Deutsch), Karte von search.ch, Footer mit localsearch-Badge und Datenschutz

Technik: Baukasten-Website von localsearch («MyWEBSITE»), Bilder vom Yext-CDN, Leaflet- und search.ch-Karte, Modernizr 2.8.3 (2014).

### Inhalt
| Bereich | Befund |
|---|---|
| Positionierung | Kein einziger Satz, wer die Firma ist, für wen sie arbeitet oder was sie auszeichnet. Der Abschnitt heisst «Über uns», enthält aber nur Leistungslisten. |
| Leistungen | Vollständig, aber als ungegliederte Stichwortlisten (25 Punkte). Keine Priorisierung, kein Nutzen für Kunden. |
| Sprache | Deutsche statt Schweizer Rechtschreibung («Fußbodenheizung», «Maßanfertigungen»), Grossschreibfehler («Sanitären Installationen»), Tippfehler («Boilerentkalung»), Punkt am Listenende («Aluminiumblech.»). |
| Referenzen | Nur unbeschriftete Bilder. Mehrere davon sind erkennbar Stockfotos (Thermostat, Werkzeug, Abfluss, Küche). Keine Projekte, keine Kundenstimmen, kein Einsatzgebiet. |
| Vertrauen | Kein Gründungsjahr, kein Team, keine Zertifikate/Verbände (z. B. suissetec), keine Öffnungszeiten, kein Notfalldienst, keine E-Mail-Adresse. |
| Kontakt | Nur Telefon und externer Buchungslink. Kein Formular. «Sprachen: Deutsch» ohne Funktion. |
| SEO | Seitentitel nur «Kurt Burri AG», keine H2-Struktur (Abschnitte als H3), keine strukturierten Daten, keine Ortsbegriffe (Diessbach, Büren, Seeland) im Text. |

### Design
| Aspekt | Befund |
|---|---|
| Typografie | Montserrat + Open Sans, Fliesstext 16 px, Listen sehr klein und eng. Keine klare Hierarchie zwischen Abschnittstitel und Inhalt. |
| Farben | Lila Akzentfarbe (#463290) aus dem Baukasten-Template, passt nicht zum Logo (Blau/Rot). |
| Hero | Niedrig aufgelöstes, verwaschenes Foto (550 × 358 px auf voller Breite hochskaliert), wirkt unscharf. |
| Layout | Zentrierte Textspalte, viel ungenutzter Platz, fast 5000 px Scrollhöhe hauptsächlich durch Listen. |
| Mobile | Funktioniert, aber die Listen werden zu einer sehr langen Textwüste. |
| Bewegung | Keine Animationen, keine Interaktion ausser Galerie-Lightbox. |
| Logo | Nur als kleines JPG mit weissem Hintergrund vorhanden; nicht für dunkle Flächen oder Retina geeignet. |

**Fazit:** Die Seite ist ein generisches Baukasten-Template. Sie erfüllt die Grundfunktion «Telefonnummer finden», vermittelt aber weder Kompetenz noch Qualität und ist als Referenz für Kunden kaum brauchbar.

## 2. Konzept für den Neuaufbau

### Leitidee
Ein Handwerksbetrieb, der Leitungen verlegt, bekommt eine Website, die durch eine Leitung erzählt wird. Ein Kupferrohr läuft vom «Haupthahn» im Hero durch alle Kapitel und füllt sich beim Scrollen mit Wasser. An jeder Station sitzt eine Muffe, die beim Erreichen aufleuchtet. Am Ende tropft es aus dem Auslass im Kontaktbereich.

### Gestaltung im Apple-Stil
- Klare Kapitel mit grossen, fetten Headlines und viel Weissraum
- Systemschrift (SF Pro auf Apple-Geräten, Figtree als Ersatz), IBM Plex Mono für technische Details
- Milchglas-Navigation, die beim Scrollen fixiert bleibt
- Bento-Raster für Leistungen statt Stichwortlisten
- Eine dunkle Kapitelfläche (Boiler) als Rhythmuswechsel
- Hell- und Dunkelmodus
- Farben aus dem Logo: Blau als Hauptfarbe, Rot nur für Wärme, Kupfer als Materialfarbe der Spenglerei

### Seitenstruktur
1. Hero «Wasser. Wärme. Blech.» mit Terminbutton und Telefonnummer
2. Überblick: drei Gewerke, ein Ansprechpartner
3. Sanitär: «Alles, was fliesst.»
4. Das neue Bad: 5-Schritte-Prozess von Beratung bis Wartung (inkl. 3D-Badplanung)
5. Heizung: «Wir heizen Ihnen kräftig ein.» (Originalslogan übernommen)
6. Boiler entkalken: eigener Verkaufsabschnitt mit Handlungsaufruf
7. Spenglerei: interaktive Materialmuster (Kupfer patiniert beim Hover)
8. Referenzen: wischbare Galerie mit Beschriftung
9. Kontakt: Adresse, Telefon mit Kopierknopf, Online-Termin, Route, Anfrageformular mit Themenwahl

### Bewegte Elemente
- Wasserleitung, die sich beim Scrollen füllt (SVG, berechnet sich bei jeder Bildschirmgrösse neu)
- Fliessendes Wasser im Rohr, Wellenimpuls an jeder erreichten Muffe, Tropfen am Auslass
- Hero-Wörter steigen gestaffelt ein, Hero-Bild zoomt beim Scrollen leicht heraus
- Prozessschritte füllen sich nacheinander
- Kalk-Balken im Boiler-Kapitel wachsen beim Einblenden
- Lichtreflex über Blechmustern, Kupfer patiniert
- Alles respektiert «Bewegung reduzieren» in den Systemeinstellungen

### Inhalte, die für einen besseren Auftritt noch fehlen
Diese Punkte kann nur die Firma liefern; der Entwurf erfindet nichts davon:

1. **Eigene Projektfotos** in hoher Auflösung (mind. 2000 px), am besten Vorher/Nachher. Stockfotos ersetzen.
2. **3–6 Referenzprojekte** mit Ort, Jahr und Leistung (z. B. «Badsanierung, Büren an der Aare, 2025»).
3. **Kundenstimmen** oder eingebundene Google-Bewertungen.
4. **Über uns**: Gründungsjahr, Inhaber, Teamfoto, Lehrbetrieb, Verbandsmitgliedschaft (suissetec).
5. **Öffnungszeiten, E-Mail, Notfall-/Pikettnummer**.
6. **Einsatzgebiet** (Gemeinden auflisten, wichtig für lokale Suche).
7. **Logo als Vektordatei** (SVG), damit es scharf und auch auf dunklem Grund funktioniert.
8. **Impressum** (in der Schweiz Pflicht) und überarbeitete Datenschutzerklärung (revDSG).

### Technische Empfehlungen
- Statische Seite oder schlankes CMS (z. B. Astro, Webflow), gehostet in der Schweiz/EU
- Bilder als AVIF/WebP in mehreren Grössen
- Formular über einen Formulardienst oder eigenes Backend mit Spam-Schutz
- Strukturierte Daten (`schema.org/Plumber`) sind im Entwurf bereits enthalten
- Google-Unternehmensprofil mit der neuen Seite verknüpfen
