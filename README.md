# Neue Weberei – Küche 🍽

Digitales Küchenmanagementsystem für die Neue Weberei als Progressive Web App (PWA).

## Features

- **Wochenplan** – Gerichte auf Tage ziehen, Notizen & Personenzahlen
- **Rezeptdatenbank** – Rezepte anlegen, bearbeiten, kopieren, mit Foto
- **Kalkulation** – Wareneinsatz, WEQ, Deckungsbeitrag pro Rezept
- **Einkaufsliste** – Automatisch aus Wochenplan generiert
- **Artikelstamm (Mutterliste)** – Lieferanten, Preise, VPE-Verwaltung
- **METRO PDF-Import** – Artikelpreise direkt aus METRO-Rechnung einlesen
- **Druckspooler** – Rezepte, Wochenplan & Kalkulationen als A4-PDF drucken
- **Stammdaten** – MwSt., Schwund-Zuschlag, WEQ-Grenzwerte

## Verwendung

### Lokal öffnen
```
index.html direkt im Browser öffnen
```

### Als PWA installieren (empfohlen)
1. Seite über einen Webserver öffnen (z.B. GitHub Pages, siehe unten)
2. Im Browser: „Zum Startbildschirm hinzufügen"
3. App läuft dann offline-fähig

### Über GitHub Pages
Die App ist erreichbar unter:
`https://<dein-username>.github.io/<repo-name>/`

## Daten
Alle Daten werden **lokal im Browser** (localStorage) gespeichert – keine Server, kein Login nötig. Daten sind pro Gerät/Browser getrennt.

## Versionen

| Version | Beschreibung |
|---------|-------------|
| v1.3 | Druckspooler (Rezepte/Wochenplan/Kalkulation), Rezept-Kopieren, MA-Features entfernt |
| v1.2 | Vollständiger Funktionsstand mit Druckspooler |

## Weiterentwicklung

Neue Features werden als `index-test.html` entwickelt und nach Abnahme in `index.html` gemergt.

| Datei | Beschreibung |
|-------|-------------|
| `index.html` | Aktuelle Produktionsversion |
| `index-v1.3.html` | Snapshot v1.3 |
| `sw.js` | Service Worker für PWA / Offline-Fähigkeit |

## Tech Stack
- Vanilla HTML/CSS/JavaScript (keine Frameworks)
- localStorage für Datenpersistenz
- PDF.js für METRO-Import
- Google Fonts (Playfair Display, DM Sans)
