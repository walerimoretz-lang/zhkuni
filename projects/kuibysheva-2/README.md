# ЖК «Университет» · ул. Куйбышева, 2 · Калининград

Landingpage und Marktanalyse für den Verkauf einer 1‑Zimmer‑Wohnung, 42,35 m².

## Inhalt

```
projects/kuibysheva-2/site/
├── index.html            Die Landingpage (Markup + CSS + JS in einer Datei)
├── politika.html         Datenschutzerklärung nach 152-ФЗ
├── LANDINGPAGE-PLAN.md   Konzept, Dramaturgie, Design-System, offene Punkte
└── assets/
    ├── config.js         ← Preis, Kontakte, Formular. Einzige zu pflegende Datei
    └── img/              Fotos in drei Größen, je als WebP und JPEG

analyse/
└── Tiefenanalyse-Kaliningrad-Kuibysheva-2.md
                          Marktanalyse Kaliningrad Juli 2026 und Wertermittlung
```

## Seite lokal ansehen

```bash
cd projects/kuibysheva-2/site && python -m http.server 8777
```
Dann `http://127.0.0.1:8777/` im Browser öffnen.

## Preis ein- oder ausblenden

In `site/assets/config.js`:

```js
showPrice: false,   // «Цена по запросу»
showPrice: true,    // zeigt price und berechnet ₽/м² aus price / area
price: 9700000,
area: 42.35,
```

Ein Wert genügt — Kopfzeile, Hero, Preisblock, Vergleichstabellen und die Sticky‑Leiste
auf dem Handy füllen sich daraus automatisch. Nach dem Speichern die Seite neu laden
(Strg + F5).

Dort stehen ebenfalls Name und Telefon der Verkäuferin, WhatsApp, Telegram, E‑Mail,
das Ziel des Kontaktformulars und der Link zum Videorundgang. Ist `formEndpoint` leer,
öffnet das Formular die Anfrage vorbefüllt in WhatsApp — dafür wird kein Server benötigt.

## Deployment

Vorgesehen ist Vercel. Die Seite ist statisch und ohne Build lauffähig: Es genügt,
den Ordner `projects/kuibysheva-2/site/` als Root zu veröffentlichen.
