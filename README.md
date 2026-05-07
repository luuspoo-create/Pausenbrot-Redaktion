# Pausenbrot · Redaktion

Redaktioneller Social-Media-Planer im Editorial-Stil von [digitalespausenbrot.ch](https://digitalespausenbrot.ch).

Eine ruhige, magazinartige Planungsoberfläche für Beiträge, Blogartikel, LinkedIn-Posts und Newsletter-Ideen rund um KI, Schule und Unterricht. Kein typisches SaaS-Dashboard, sondern eine digitale Zeitung für Content-Planung.

## Aufbau

- **Wochenplanung** — sieben Tage, vier Kanäle, ein Editorial.
- **Content-Pipeline** — Idee · In Arbeit · Bereit (drei magazinartige Spalten).
- **Kanäle** — LinkedIn, Blog, Newsletter, Instagram in einer ruhigen Übersicht.
- **Aus dem Kalender** — die nächsten Veröffentlichungen als redaktionelle Teaser.
- **Ideenarchiv** — sortiert nach Reifegrad (Rohidee · Ausformuliert · Reif).
- **Analyse** — vier ruhige Kennzahlen statt grosser Diagramme.

## Stack

Eine einzelne, in sich geschlossene HTML-Datei. Kein Build-Step, keine Frameworks, keine externen Skripte. Schriften: Playfair Display, Source Serif 4, IBM Plex Mono via Google Fonts.

## Lokal öffnen

```sh
open index.html
```

Oder über einen einfachen Webserver:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

## Hosting

Geeignet für GitHub Pages, Netlify, Vercel oder jeden statischen Host. Für GitHub Pages: Settings → Pages → Source: `main` / root.

## Lizenz

© Lucca Spohn · Digitales Pausenbrot. Alle Rechte vorbehalten.
