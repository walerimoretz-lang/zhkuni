# Landingpage-Plan
## Куйбышева 2 · ЖК «Университет» · Kaliningrad

**Ziel:** In möglichst kurzer Zeit Vertrauen und Neugier wecken — bei einer Zielgruppe, die das Objekt überwiegend **nicht besichtigen wird, bevor sie sich entscheidet.**
**Stand:** 6. August 2026 · Umgesetzt in `landing/index.html`

> **Änderungen gegenüber der Erstfassung** (Vorgaben der Eigentümerin vom 6.8.2026):
> Ansprechpartnerin **Светлана, +7 950 077 6159** · **kein Stellplatz im Verkauf** — sämtliche Paket‑ und Parkinhalte entfernt · **Preis auf Anfrage**, über `assets/config.js` jederzeit einschaltbar · russische Datenschutzerklärung erstellt und verlinkt · Formular verschickt Anfragen ohne Server direkt über WhatsApp.

---

## 1. Die strategische Ausgangslage in fünf Sätzen

1. Über ein Drittel der Kaliningrader Käufer kommt von außerhalb der Region; 65 % aller Interessenten an Kaliningrader Inseraten wohnen in anderen Regionen. Viele kaufen **remote, ohne die Wohnung gesehen zu haben**.
2. Genau diese Fernkäufer wurden in Kaliningrad nachweislich enttäuscht — die lokale Presse dokumentiert überzogene Renditeversprechen und „negative Kapitalisierung". **Misstrauen ist der Normalzustand des Zielkunden.**
3. Juli 2026 ist ein Käufermarkt: Angebotspreise steigen, Nachfrage stagniert, überteuerte Objekte bleiben monatelang stehen. Im eigenen Haus stehen vier Wohnungen seit 10–14 Monaten.
4. Das Objekt kostet mehr als eine durchschnittliche Einzimmerwohnung. Der zentrale Einwand — *«за эти деньги я возьму двушку»* — ist vorhersehbar und muss **vor** der Preisnennung entwaffnet werden.
5. Auf ЦИАН und Авито steht dieses Objekt neben 11.500 anderen Einzimmerwohnungen in identischem Layout, sortiert nach Preis. Das ist die falsche Vergleichsachse. **Die Landingpage existiert, um die Vergleichsachse zu wechseln.**

**Daraus folgt die Leitidee der Seite:**

> **Radikale Nachprüfbarkeit als Verkaufsargument.**
> Nicht „glauben Sie mir" — sondern „prüfen Sie es nach, hier sind die Zahlen und die Quelle".
> In einem Markt, in dem Fernkäufer regelmäßig enttäuscht werden, ist Überprüfbarkeit das knappste Gut. Wer sie als Erster anbietet, gewinnt.

---

## 2. Die Dramaturgie: Vertrauen und Neugier in 5 Sekunden, 30 Sekunden, 3 Minuten

Vertrauen und Neugier sind zwei verschiedene Mechanismen und brauchen unterschiedliche Mittel. Die Seite bedient beide parallel, nicht nacheinander.

### Sekunde 0–5 — der Vertrauensfilter

Was in den ersten fünf Sekunden sichtbar sein **muss**:

| Element | Signal | Umsetzung |
|---|---|---|
| Ein echtes Foto, sofort, bildfüllend | „Das ist eine reale Wohnung, kein Rendering" | Hero: die Schlafzone mit Spiegel-Trennwand — das ungewöhnlichste und schönste Bild des Bestands |
| **Exakte Adresse**, nicht „Zentrum" | „Ich kann das auf der Karte prüfen" | `Калининград · ул. Куйбышева, 2 · ЖК «Университет» · Ленинградский район` |
| Der Preisstatus wird **ausgesprochen**, nicht verschwiegen | „Man weiß, woran man ist" | Ruhige Zeile in der CTA-Reihe: «Цена по запросу →», Sprung zum Preisblock, wo offen erklärt wird warum |
| „Продаёт собственник — без комиссии" | „Kein Makler, kein Aufschlag" | Trust-Zeile direkt unter den CTAs |
| „Онлайн-показ по видеосвязи" | „Ich muss nicht erst fliegen" | Trust-Zeile — spricht den Fernkäufer direkt an |

Was Vertrauen in den ersten Sekunden **zerstört** und deshalb fehlt: Stockfotos, Renderings, ein Preis, der erst nach dem Ausfüllen eines Formulars herausgerückt wird, Ausrufezeichen, Countdown, Portal-Blau, Gold-Verlauf, Cookie-Overlay über dem Hero.

> **Zur Entscheidung „Preis auf Anfrage":** Sie ist getroffen und umgesetzt. Damit sie nicht als Ausweichen wirkt, ist sie auf der Seite an drei Stellen **begründet** statt bloß behauptet — im Preisblock, im FAQ («Почему цена не указана на сайте?») und im CTA-Text («Узнать цену и условия» statt «Оставить заявку»). Ausdrücklich zugesagt wird: kein Formular als Vorbedingung, die Zahl kommt sofort im ersten Kontakt. Das ist der Unterschied zwischen Zurückhaltung und Gatekeeping. Die Abwägung mit Zahlen steht in der Tiefenanalyse, Abschnitt 7.5a — **in den Portalinseraten muss der Preis stehen**, dort ist er Pflicht- und Filterfeld.

### Sekunde 5–30 — der Neugier-Haken

Die Überschrift ist bewusst kein Angebot, sondern ein **Widerspruch, der aufgelöst werden will**:

> **«42 метра, которые живут как 60»**

Der Leser weiß, dass 42 m² klein sind. Die Behauptung widerspricht seiner Erfahrung — und der Auflösungsdrang trägt ihn über die ersten drei Bildschirme. Aufgelöst wird sie mehrfach: separate Küche 10,41 m², ausfahrbare Trennwand, +4,02 m² beheizte Loggia als Arbeitszimmer, durchgängiges Einbau-Stauraumsystem.

Direkt darunter die **Faktenleiste** — sechs Zahlen, kein Fließtext: `42,35 м² · +4,02 м² тёплая лоджия · 10,41 м² отдельная кухня · 8/9 этаж · 2021 · 2,80 м`. Zahlen lesen sich schneller als Sätze und wirken geprüft.

### Sekunde 30 – Minute 3 — das Verstehen

Reihenfolge nach dem Prinzip **Atmosphäre → Verstehen → Zahl → Bitte**. Die Umkehrung dieser Reihenfolge ist genau das, was Portal-Inserate transaktional wirken lässt.

---

## 3. Sektionsplan mit Begründung

| # | Sektion | Aufgabe | Warum an dieser Stelle |
|---|---|---|---|
| 1 | **Hero** | Vertrauensfilter + Neugier‑Haken | Das Foto ist das Produkt. Ein Bild, kein Karussell — ein Karussell signalisiert, dass kein einziges Bild gut genug ist |
| 2 | **Почему это редкий лот** — 6 Karten | Den Einwand „austauschbare Einzimmerwohnung" sofort brechen | Bevor der Preis kommt, muss die Kategorie gewechselt sein. Öffnet mit der Knappheit: 4 von 154 Wohnungen im Verkauf, 44 Stellplätze im ganzen Haus |
| 3 | **Локация** (dunkel) | Nachprüfbarkeit demonstrieren | Erste Farbumkehr = visuelle Zäsur. Entfernungen mit **echten Routing‑Werten**, nicht mit Bauträger‑Marketing |
| 4 | **Планировка** — interaktiv | Neugier in Verstehen überführen | Die wirksamste Einzelinteraktion einer Objektseite: klickbare Hotspots auf dem vermaßten Plan → Raumbeschreibung. Hier wird der Widerspruch der Headline aufgelöst |
| 5 | **Интерьер** — Galerie mit Reitern | Emotion, Detail, Handwerk | Nach dem Verstehen kommt das Wollen. Reiter statt endlosem Scrollen, damit der Nutzer steuert |
| 6 | **Что входит в цену** (dunkel) | Aus „mit Möbeln" eine zählbare Liste machen | **Preisvorbereitung.** Wer 24 konkrete Positionen mit Markennamen gelesen hat, bewertet die Zahl in Sektion 7 anders |
| 7 | **Цена** | Die Zahl nennen und sofort einordnen | Kommt erst nach fünf Sektionen — dann aber vollständig: Gesamtpreis → ₽/м² → Vergleichstabelle mit Quelle und Datum → Verhandlungsposition |
| 8 | **Для инвестора** (dunkel) | Glaubwürdigkeit durch Ehrlichkeit | Öffnet mit „ohne rosa Brille" und **nennt den Festgeldzins, der höher ist**. Wer den eigenen schwächsten Punkt zuerst nennt, wird bei allem anderen geglaubt |
| 9 | **Дом и двор** | Das Haus verkaufen, nicht nur die Wohnung | Fassade, Eingangsbereich, Tiefgarage, BFU. Beantwortet „wo lebe ich eigentlich?" |
| 10 | **Сделка** | Den Fernkauf entängstigen | Vier Schritte + Dokumentenliste. Adressiert genau die dokumentierte Enttäuschung von Fernkäufern |
| 11 | **FAQ** | Die acht Einwände beantworten, die sonst zum Abbruch führen | Öffnet mit dem härtesten: „Почему дороже средней однокомнатной?" |
| 12 | **Контакт** (dunkel) | Die Bitte | Named human, Telefon, Telegram, WhatsApp, 3‑Feld‑Formular |
| 13 | **Footer** | Rechtliche Sauberkeit | Nicht‑Oferte‑Hinweis, Flächenvorbehalt, Hinweis dass die Fotos aus der verkauften Wohnung stammen |

**Rhythmus:** hell → hell → **dunkel** → sand → hell → **dunkel** → sand → **dunkel** → hell → sand → hell → **dunkel**. Die Farbwechsel sind die Kapitelgrenzen; sie ersetzen Trennlinien und geben dem Scrollen Takt.

---

## 4. Vertrauensarchitektur — die zwölf konkreten Mittel

| Mittel | Umsetzung auf der Seite |
|---|---|
| 1. Nur echte Fotos | 22 Originalaufnahmen aus der Wohnung, keine Renderings, kein Stockmaterial, kein Fisheye |
| 2. Geprüfte statt beworbene Entfernungen | Bauträger wirbt „5 Min zur пл. Василевского" — real 10 Min. Die Seite nennt **754 m / 10 Min** und lädt zur Kartenprüfung ein |
| 3. Quellen an jeder Marktzahl | „Срез на 5 августа 2026", „данные августа 2026", Nennung dass es **Angebots‑, keine Abschlusspreise** sind |
| 4. Der eigene schwache Punkt zuerst | Investorenblock nennt offen: Festgeld 12,8–16 % schlägt die Mietrendite. „Wenn Sie nur Prozente wollen, nehmen Sie das Festgeld" |
| 5. Konkurrenz zeigen, nicht verstecken | Vergleichstabelle mit vier fremden Objekten — inklusive des **Rohbaus im eigenen Haus zu 232.900 ₽/м²** |
| 6. Zählbare statt adjektivische Ausstattung | 24 Positionen mit Marken (Bosch, Samsung, Homematic IP) statt „hochwertige Ausstattung" |
| 7. Inventar als Vertragsanlage | „Опись мебели и техники (приложение к ДКП)" — macht die Zusage einklagbar |
| 8. Dokumente **vor** der Anzahlung | Acht Positionen namentlich gelistet |
| 9. Sichere Abwicklung benannt | Аккредитив / Bankservice / elektronische Registrierung |
| 10. Ein Mensch, kein Callcenter | Name, Foto, Direktnummer, Telegram, WhatsApp — „отвечаю лично" |
| 11. Der Verhandlungsstandpunkt wird ausgesprochen | „Это цена предложения. Разумный торг… обсуждается предметно, а не просто так" — statt dem Käufer die Vermutung eines großen versteckten Rabatts zu überlassen |
| 12. Rechtliche Ehrlichkeit im Footer | Nicht‑Oferte, Flächen nach ЕГРН zu präzisieren, Renditerechnung keine Anlageempfehlung |

> **Der wichtigste Punkt ist Nr. 4.** Der Investorenblock, der offen sagt, dass ein Bankdepot mehr Prozente bringt, ist der teuerste und wirksamste Satz der ganzen Seite. Er kostet den Investor als Käufer — und gewinnt die Glaubwürdigkeit für alle anderen Zahlen.

---

## 5. Neugier-Architektur — die sechs Mechanismen

1. **Die paradoxe Headline.** „42 метра, которые живут как 60" erzeugt eine offene Schleife, die erst in Sektion 4 geschlossen wird.
2. **Der interaktive Grundriss.** Fünf nummerierte Hotspots auf dem vermaßten Designprojekt. Klick → Raumbeschreibung. Der Nutzer erkundet selbst statt zu konsumieren; das ist der Unterschied zwischen Ansehen und Verstehen.
3. **Die versteckte Fläche.** „42,35 m² nach Dokumenten + 4,02 m² warme Loggia = tatsächlich 46,4 m² — beim Quadratmeterpreis gerechnet auf 42,35." Eine Zahl, die man nicht vermutet.
4. **Die zählbare Komplettierung.** Die Inventarliste liest sich wie ein Kassenzettel, den man nicht erwartet hat: Zerkleinerer, Hygienedusche, LAN auf der Loggia, Geschirr.
5. **Die Rechnung „selbst machen vs. fertig kaufen".** Zehn Positionen mit Preisen. Wer eine Tabelle liest, rechnet mit — und wer mitrechnet, ist beteiligt.
6. **Der Renditerechner.** Vier Schieberegler, sofortige Reaktion. Interaktion erzeugt Bindung, selbst wenn das Ergebnis nüchtern ist.

**Bewusst nicht verwendet:** Countdown, „noch 2 Interessenten", Popup nach 15 Sekunden, Exit‑Intent, Chat‑Bubble mit Fake‑Nachricht. In diesem Preissegment und bei dieser Zielgruppe kosten sie mehr Vertrauen, als sie an Aufmerksamkeit bringen.

---

## 6. Design-System

### Farbe — Disziplin statt Dekoration
Ausgezeichnete Immobilienseiten 2026 arbeiten mit **zwei bis drei Farben insgesamt**. Zurückhaltung ist das Luxussignal, nicht Ornament.

| Rolle | Wert | Herkunft |
|---|---|---|
| Ink (Tiefdunkel, warm) | `#12100E` | aus den Nachtaufnahmen der Wohnung |
| Paper (Warmweiß) | `#FBF9F6` | — |
| Sand (Sektionsfläche) | `#EFE8DD` | Wandfarbe der Wohnung |
| **Akzent Messing** | `#B08D57` / hell `#D6B788` | warmes LED‑Licht und Eichenfronten |
| Sekundär Petrol | `#0E5C63` | Sofafarbe — sparsam |

**Regel:** Der Akzent erscheint auf höchstens drei Elementen pro Bildschirm (CTA, aktiver Zustand, Preis). Alles andere ist Ink auf Paper.

**Ausdrücklich verboten:** Portal‑Blau (`#0066CC`, `#2F80ED` — die Sprache von ЦИАН/Авито/Домклик, sie stuft das Objekt zurück in die Datenbankzeile), echtes Gold (`#FFD700`, Goldverläufe — liest sich im russischen Markt als „евроремонт" der 2000er), SaaS‑Violett, reines Warnrot, Farbverläufe auf großen Flächen.

### Typografie — der Punkt, an dem russische Premiumseiten scheitern

Die schönen Display‑Schriften westlicher Luxus‑Templates (Cinzel, Marcellus, Gilda Display) haben **kein Kyrillisch**. Wer sie einsetzt, bekommt für jede russische Überschrift eine Systemschrift‑Ersatzdarstellung — und die Seite verrät sich sofort als übersetztes Template.

| Rolle | Schrift | Warum |
|---|---|---|
| Display | **Prata** | Hochkontrast‑Didone, **kyrillisch von Grund auf entworfen**. Liest sich als Modemagazin und zurückhaltender Luxus. Der beste Einzelgriff für ein russisches Premiumobjekt |
| Text/UI | **Golos Text** | Kyrillisch‑first‑Grotesk mit hervorragendem Rhythmus, sehr neutral. Der beste Standard für russischen Fließtext |

**Ebenfalls vermieden:** Montserrat und Raleway. Kyrillisch ist in Ordnung, aber sie sind die Signaturschriften jedes Tilda‑Standardtemplates und lesen sich für genau diesen Käufer als „an einem Nachmittag gebaut".

**Kyrillische Satzdetails, die umgesetzt sind:** Zeilenhöhe 1,65 im Fließtext (Kyrillisch braucht mehr Durchschuss als Latein, weil Ober‑ und Unterlängen fehlen und der Satz dichter wirkt) · Versalien mit +0,19 em Sperrung · Display mit −0,02 em · Ziffern durchgängig `tabular-nums` · Prata hat nur einen Schnitt, deshalb ist jede Kunstfettung explizit unterbunden · das ₽‑Zeichen (U+20BD) ist auf Vorhandensein geprüft.

**Ausbaustufe:** Eine lizenzierte russische Foundry‑Schrift ist der günstigste Sprung von „gutes Template" zu „beauftragte Marke" — TT Ramillas (TypeType) als Display, CoFo Gothic oder Brownfox Formular als Text, zusammen etwa 140–300 $. Ein russischsprachiger Premiumkäufer liest kyrillische Formen fließend und bemerkt schlechte.

### Layout
Redaktionelles, asymmetrisches Raster — Magazinseiten, keine Kartengitter. Ein Kartengitter sagt „Katalog von vielen", eine Magazinseite sagt „das einzige". 12 Spalten, nie symmetrisch gefüllt. Sektionsabstand 72–132 px (Desktop) / 52–88 px (Mobil). Maximale Textbreite 62–68 kyrillische Zeichen. Fließtext niemals zentriert.

### Bewegung
Wie ein Kameramann, nicht wie ein Spielzeug. Scroll‑Reveal 750 ms mit `cubic-bezier(.22,.61,.36,1)`, 20 px Versatz, 90 ms Staffelung. Hero‑Bild mit 26‑Sekunden‑Langsamzoom von 1,075 auf 1,0. Keine Bounces, keine Rotationen, kein Parallax über 0,85× Scrollgeschwindigkeit.

`prefers-reduced-motion` schaltet **alles** ab — Zoom, Puls, Reveal, Übergänge. Alle Inhalte animieren **von sichtbar**, nicht **zu sichtbar**: Ohne JavaScript bleibt die Seite vollständig lesbar.

### Bildstrategie
- Ein Fotograf, eine Objektiv‑Familie, ein Weißabgleich über alle Aufnahmen. **Ein einziger Handy‑Schnappschuss in einem professionellen Satz zerstört den Premium‑Eindruck der ganzen Seite** — das Auge findet den Bruch im Weißabgleich, bevor es eine Zeile liest.
- Drei Größen (640/1100/1800) × zwei Formate (WebP + JPEG) über `<picture>`.
- Hero: `preload` mit `fetchpriority="high"`, **niemals** `loading="lazy"` — das LCP‑Bild lazy zu laden erzeugt garantiert Verzögerung.
- Alle anderen Bilder `loading="lazy"` mit gesetzten `width`/`height` gegen Layout‑Sprünge.
- Alt‑Texte auf Russisch und beschreibend („Спальная зона с зеркальной перегородкой в стиле лофт"), nicht „photo1".

### Zugänglichkeit
Text niemals direkt auf unbearbeitetem Foto — der Hero trägt einen doppelten Verlaufs‑Scrim. Fließtext ≥ 16 px. Tastaturpfade für Hotspots, Lightbox (Esc, Pfeiltasten), Reiter und Sticky‑CTA. `lang="ru"` gesetzt. Getestet bei 200 % Zoom und 320 px Breite.

Diese Kategorie liefert hier systematisch schlecht ab: Eine Immobilienseite, die im Juni 2026 „Site of the Day" wurde, erreichte bei Accessibility nur 6,6 von 10 — ihr schwächster Wert. Der praktische Preis ist direkt: Ein 55‑jähriger Käufer, der am Telefon in der Sonne den Preis nicht lesen kann, geht.

---

## 7. Conversion-Mechanik

### Handlungsaufforderungen — Hierarchie
| Ebene | Text | Ort |
|---|---|---|
| Primär | **«Записаться на просмотр»** | Hero, Preisblock, Kontakt, Sticky‑Leiste, Kopfzeile |
| Sekundär | «Посмотреть планировку» | Hero — für den, der noch nicht sprechen will |
| Tertiär | «Цена по запросу →» | Hero — führt direkt zum Preisblock, wo die Zurückhaltung begründet wird |

Ausdrücklich **nicht**: „Оставить заявку", „Узнать цену", „Подробнее". Das erste ist nichtssagend, das zweite versteckt den Preis, das dritte fordert nichts.

### Kanäle
Telefon, **Telegram**, WhatsApp, E‑Mail und ein Formular mit drei Feldern (Name, Kontakt, Wunschzeit) plus optionaler Herkunftsstadt. Telegram und WhatsApp stehen gleichrangig neben dem Telefon: In Russland findet das Gespräch dort statt, und ein Fernkäufer aus einer anderen Zeitzone ruft nicht an, er schreibt.

Das Feld **„Из какого вы города"** ist kein Datensammeln, sondern Qualifizierung: Die Antwort entscheidet, ob als Nächstes ein Termin oder ein Videorundgang angeboten wird.

### Orientierung auf einer langen Seite
Die Seite ist rund 15.000 px hoch. Ohne Orientierung weiß der Nutzer nicht, ob Preis, Grundriss oder Lage noch kommen — und der häufigste Abbruchgrund ist „ich habe die Zahl nicht gefunden".
- **Fortschrittsleiste** oben, 2 px, Messing.
- **Kapitelnavigation** rechts, acht Punkte mit Beschriftung bei Hover/Fokus, aktiver Punkt in Messing. Ersetzt das Menü.
- **Sticky‑Kopfzeile** mit Preis, sobald der Hero verlassen ist.
- **Sticky‑Leiste unten** auf Mobil mit Preis und CTA, ausgeblendet sobald der Kontaktbereich sichtbar ist.
- Anker in der URL, damit `…/#price` direkt teilbar ist — genau so wandern diese Links in Russland durch Telegram und WhatsApp.

### Messung
| Ereignis | Warum |
|---|---|
| `scroll_price` (Preisblock erreicht) | Die eigentliche Qualifizierungsschwelle |
| `plan_hotspot_click` | Misst echtes Interesse, nicht Sitzungsdauer |
| `calc_used` | Investorensegment identifizieren |
| `cta_click` je Position | Welcher Ort trägt |
| `contact_submit` mit Herkunftsstadt | Zielgruppen‑Zuordnung |
| Scrolltiefe 25/50/75/100 % | Wo bricht es ab |

Yandex.Metrika mit Webvisor ist hier aussagekräftiger als Google Analytics — russischer Traffic, russische Referrer, Heatmap inklusive. **Erst nach Interaktion oder im Leerlauf laden**, nie vor dem ersten Rendern.

---

## 8. Was vor der Veröffentlichung erledigt werden muss

**Erledigt am 6.8.2026** ✔

- Ansprechpartnerin und Telefon eingetragen: Светлана, +7 950 077 6159 (WhatsApp aus derselben Nummer)
- Rechtsaussagen bestätigt: „Продаёт собственник", „без комиссии", Dokumentenliste
- Stellplatz: gehört **nicht** zum Verkauf → alle Park- und Paketinhalte entfernt
- Amtliche Fläche 42,35 m² bestätigt
- Preis: «Цена по запросу», über `assets/config.js` umschaltbar
- Formular: funktioniert ohne Server — die Anfrage öffnet vorbefüllt in WhatsApp
- Datenschutzerklärung nach russischem Recht (152‑ФЗ) erstellt: `politika.html`, verlinkt in Formular und Fußzeile

**Noch offen, blockierend für den Launch:**

1. **Telegram‑Nutzername** — in `config.js` unter `telegram` eintragen, dann erscheint der Button automatisch. Telegram ist in Russland der Hauptkanal für genau diese Gespräche; ohne ihn fehlt der bequemste Kontaktweg.
2. **Rechtsdetails für den Block „Сделка"**: Eigentumsdauer, Anzahl Eigentümer, Belastungen, gemeldete Personen. Aktuell wird nur die Dokumentenliste gezeigt — das ist korrekt, aber konkrete Angaben („единственный собственник", „более 5 лет в собственности") wären deutlich stärker. Nur veröffentlichen, was belegt ist.
3. **Hosting** — Vercel ist vorgesehen, kommt laut Absprache später.

**Stark empfohlen vor dem Launch:**

4. **Video‑Rundgang** (3–5 Min, Hochformat, ungeschnitten in einem Take, mit Blick aus allen Fenstern) — Link in `config.js` unter `videoUrl`. Für Fernkäufer das wichtigste fehlende Element; ersetzt die halbe Besichtigung.
5. **Autorennachweis**: „Проект: [Designer/Büro], [Jahr]". Eine anonyme Designerwohnung ist ein Widerspruch in sich.
6. **Himmelsrichtung** auf dem Grundriss ergänzen — russische Käufer fragen konstant danach, und in Kaliningrad mit kurzen Wintertagen ist die Besonnung ein echtes Kaufkriterium.
7. **4–6 Material‑Makroaufnahmen** (Steinkante, Griff, Fugenbild, Armatur, Textilstruktur, Holzmaserung). Nichts sagt so schnell „teuer".
8. **Nebenkostenquittungen** der letzten 12 Monate als PDF — belegt den Vorteil der autonomen Gasheizung.

**Nach dem Launch:**

9. Deployment auf Vercel, HTTPS, eigene Domain (z. B. `kuibysheva2.ru`).
10. `og:image` prüfen — so sieht der Link in Telegram und WhatsApp aus, und dort wird er geteilt.
11. Yandex.Metrika + Ziele einrichten.
12. Link in alle Portalinserate, in die Telegram‑Signatur und in die Direktansprache. **In den Portalinseraten den Preis nennen** — dort ist er Pflicht- und Filterfeld.

---

## 9. Was diesem Plan fehlt — offen benannt

Der Rechercheauftrag zu **russischen Conversion‑Konventionen** (Struktur, CTA‑Formulierungen, Lead‑Magneten, Mobilanteil 2026) ist technisch fehlgeschlagen; das Websuche‑Budget der Sitzung war danach erschöpft. Die Empfehlungen in Abschnitt 7 stützen sich deshalb auf **beobachtete Konventionen russischer Premiumkataloge** (kf.expert, sminex.com, metrium.ru, jeweils abgerufen am 5.8.2026), auf die Marktrecherche dieses Projekts und auf allgemeine Handwerkspraxis — **nicht auf publizierte Nutzerforschung**. Sie sind als informierte Konvention zu lesen, nicht als Evidenz.

Ebenso fehlt: keine Kaliningrad‑spezifische Landingpage konnte zum Vergleich untersucht werden; lokale Konvention kann von Moskauer Konvention abweichen (etwa eine geringere Toleranz für „Цена по запросу" und eine stärkere Erwartung, dass die Verhandlungsposition ausgesprochen wird).

**Empfehlung:** Die Seite nach vier Wochen anhand echter Daten nachschärfen (Scrolltiefe, Absprungpunkt, Formularabbrüche) statt jetzt weiter zu theoretisieren. Ein A/B‑Test der Headline gegen eine nüchterne Variante («Дизайнерская квартира 42,35 м² у Верхнего озера») wäre der erste sinnvolle Test.

---

## 10. Technische Umsetzung

**Stack:** eine einzelne `index.html`, kein Framework, kein Build. CSS und JS inline, Bilder in `assets/img/`. Gesamtgewicht ohne Bilder unter 60 KB.

Begründung: Die Seite muss von jedem Hosting laufen, ohne Deployment‑Kette gepflegt werden können, und in einem Markt schnell sein, in dem Mobilfunk nicht überall gleich gut ist. Ein Framework würde hier nichts hinzufügen und einiges kosten.

**Struktur:**
```
landing/
├── index.html              Vollständige Seite (Markup + CSS + JS)
├── politika.html           Datenschutzerklärung nach 152-ФЗ
├── LANDINGPAGE-PLAN.md     dieses Dokument
└── assets/
    ├── config.js           ← EINZIGE Datei für Preis, Kontakte, Formular
    └── img/                21 Motive × 3 Größen × 2 Formate
```

**Preis ein- oder ausschalten** — in `assets/config.js`:
```js
showPrice: false,   // «Цена по запросу»
showPrice: true,    // zeigt price und berechnet ₽/м² aus price / area
price: 9700000,
area: 42.35,
```
Ein Wert genügt: Kopfzeile, Hero, Preisblock, Vergleichstabelle, Marktvergleich und die
Sticky‑Leiste auf dem Handy füllen sich daraus automatisch. Danach nur Seite neu laden.

**Lokale Vorschau:**
```bash
cd "D:/01 Antigrafity Projekte/kuibesheva kw31/landing" && python -m http.server 8777
```

**Enthaltene Funktionen:** interaktiver Grundriss mit fünf Hotspots · Galerie mit sechs Reitern und Lightbox (Tastatur) · Renditerechner mit vier Reglern · Fortschrittsleiste · Kapitelnavigation mit aktivem Zustand · Sticky‑Kopfzeile · Sticky‑Leiste auf Mobil · Scroll‑Reveal mit `IntersectionObserver` · Formular mit WhatsApp‑Fallback ohne Server · zentrale Konfigurationsdatei · vollständige `prefers-reduced-motion`‑Unterstützung.

**Geprüft:** 1440×900, 1280×720, 390×844 · keine Konsolenfehler · kein horizontales Scrollen · alle Bilder laden · Rechner rechnet korrekt · Hotspots sitzen an den richtigen Räumen · Preisschalter in beiden Stellungen getestet.
