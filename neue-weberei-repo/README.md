# Neue Weberei – Küche 🍽

Digitales Küchenmanagementsystem als Progressive Web App (PWA).

## Features
- **Wochenplan** – Gerichte planen, Notizen & Personenzahlen
- **Rezeptdatenbank** – Rezepte anlegen, bearbeiten, kopieren, mit Foto
- **Kalkulation** – Wareneinsatz, WEQ, Deckungsbeitrag
- **Einkaufsliste** – Automatisch aus Wochenplan generiert
- **Artikelstamm** – Lieferanten, Preise, VPE-Verwaltung
- **METRO PDF-Import** – Artikelpreise aus METRO-Rechnung einlesen
- **Druckspooler** – Rezepte, Wochenplan & Kalkulation als A4 drucken

## App öffnen
👉 https://berndreutemann.github.io/neue-weberei/

## Dateien
| Datei | Beschreibung |
|-------|-------------|
| `index.html` | Aktuelle Produktionsversion (v1.3) |
| `index-v1.3.html` | Snapshot v1.3 |
| `sw.js` | Service Worker (PWA/Offline) |

## Daten
Alle Daten werden lokal im Browser gespeichert (localStorage) – kein Server, kein Login.

## Update einspielen
1. Neue `index.html` in diesen Ordner kopieren
2. GitHub Desktop → Commit → Push
3. Nach ~1 Minute automatisch live
