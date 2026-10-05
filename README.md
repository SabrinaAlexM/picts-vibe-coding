# Vibe Coding und kreatives Arbeiten mit KI

**PICTS Aufbaumodul: Künstliche Intelligenz in der Schule · Halbtag 4**

PICTS erleben KI als Werkzeug zur Gestaltung und Problemlösung mit praktischen Anwendungen.

Interaktives Lernmodul für einen Kurshalbtag. Es begleitet den ganzen Nachmittag: am Beamer als Präsentation und auf den Geräten der Teilnehmenden als Arbeitsanleitung mit Prompts zum Kopieren.

## Inhalt

Das Modul ist als Expedition in sieben Etappen aufgebaut:

| Etappe | Thema | Unterkapitel |
|---|---|---|
| 0 · Basislager | Start: Ziele, Ablauf, Vorbereitung | |
| 1 · Warm-up | Practice-Runde mit Timer | |
| 2 · Kompass | Was ist Vibe Coding? | |
| 3 · Erster Gipfel | Von der Idee zum Produkt | 3.1 Projektstart · 3.2 Bauen · 3.3 Zeigt her! |
| 4 · Abzweigung | Weiterdenken | 4.1 Kreativ-Labor · 4.2 Ideenbörse Vibe Coding |
| 5 · Rastplatz | Code verstehen (PRIMM) | 5.1 Teilen und Versionieren |
| 6 · Wegweiser | PICTS-Perspektive mit fünf Fallszenarien | |
| 7 · Heimweg | Transfer und Weiterlernen | |

Wiederkehrende Kästen «Kennt ihr aus dem Informatikunterricht» zeigen Bezüge zu Pair Programming, Problemzerlegung, Debugging, PRIMM und Versionieren.

## Nutzung

**Online:** Die veröffentlichte Version im Browser öffnen. Mit den Pfeiltasten links und rechts wird geblättert, Bereiche mit Plus lassen sich aufklappen.

**Lokal:** `index.html` herunterladen und per Doppelklick im Browser öffnen. Es braucht keine Installation.

**Direkt auf ein Kapitel verlinken:** An die Adresse einen Anker anhängen, zum Beispiel `#kreativ` für das Kreativ-Labor oder `#picts` für die Fallszenarien.

| Anker | Seite |
|---|---|
| `#basislager` | Start |
| `#warmup` | Practice-Runde |
| `#begriff` | Was ist Vibe Coding? |
| `#idee-produkt` | Von der Idee zum Produkt |
| `#projektstart` | 3.1 Projektstart |
| `#bauen` | 3.2 Bauen |
| `#zeigt-her` | 3.3 Zeigt her! |
| `#weiterdenken` | Weiterdenken |
| `#kreativ` | 4.1 Kreativ-Labor |
| `#ideen` | 4.2 Ideenbörse |
| `#code` | Code verstehen |
| `#teilen` | 5.1 Teilen und Versionieren |
| `#picts` | PICTS-Perspektive |
| `#transfer` | Transfer |
| `#impressum` | Impressum |

## Veröffentlichen

**Vercel:** Repository in Vercel importieren. Da es nur eine statische `index.html` ist, sind keine weiteren Einstellungen nötig.

**GitHub Pages:** Im Repository unter *Settings → Pages* als Quelle den Branch `main` und den Ordner `/ (root)` wählen.

## In ILIAS einbetten

Im Seiteneditor **«Externen Inhalt einfügen»** wählen und folgendes Snippet einfügen. Die Adresse muss je nach ILIAS-Konfiguration vom Admin als erlaubte Web-Ressource freigegeben werden.

```html
<iframe src="https://DEINE-ADRESSE" width="100%" height="850" style="border:0" allow="clipboard-write" title="Halbtag 4: Vibe Coding und kreatives Arbeiten mit KI"></iframe>
```

## Inhalte anpassen

Alle Inhalte stehen in `index.html` im Abschnitt `INHALT`, im Array `STAGES`. Jede Etappe hat eine Liste von Seiten (`pages`), jede Seite hat eine `id`, einen `title`, optional eine Unterkapitelnummer (`sub`) und ihren Inhalt als HTML (`html`).

Wiederverwendbare Bausteine:

- `P("Titel", "Text")` erzeugt eine Prompt-Box mit Kopieren-Knopf.
- `MORE("Titel", "HTML")` erzeugt einen aufklappbaren Bereich.
- `INFO("Titel", "HTML")` erzeugt einen Kasten «Kennt ihr aus dem Informatikunterricht».
- `CHECKS([...])` erzeugt eine Checkliste zum Abhaken.
- `L("Text", "URL")` erzeugt einen Link, der in einem neuen Tab öffnet.

Farben und Schriften stehen ganz oben im `<style>`-Bereich unter `:root`.

## Technik und Datenschutz

- Eine einzige HTML-Datei, ohne Build-Schritt und ohne externe Skripte.
- Keine Speicherung von Daten, keine Cookies, kein Tracking. Checklisten werden beim Neuladen zurückgesetzt.
- **Schriften:** Die Schriften (Bricolage Grotesque, Atkinson Hyperlegible, IBM Plex Mono) werden von Google Fonts geladen. Dabei wird die IP-Adresse der Nutzenden an Google übermittelt. Wer das vermeiden will, kann die Schriften selbst hosten oder die Zeile mit `fonts.googleapis.com` entfernen. Dann werden Systemschriften verwendet.

## Stand

Angaben zu Werkzeugen, Kosten und Altersgrenzen entsprechen dem Stand Oktober 2026 und können sich ändern.

## Autorin

**Sabrina Meier**
Dozentin Medien und Informatik
Co-Leiterin Fachstelle Schule und Digitalität
Pädagogische Hochschule Thurgau

Erstellt mit Unterstützung von KI.

## Lizenz

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de)

Dieses Werk ist lizenziert unter einer [Creative Commons Namensnennung, Nicht kommerziell, Weitergabe unter gleichen Bedingungen 4.0 International Lizenz](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de).

Bei Weiterverwendung bitte nennen: *Sabrina Meier, Pädagogische Hochschule Thurgau, «Vibe Coding und kreatives Arbeiten mit KI», CC BY-NC-SA 4.0.*

Externe Links führen zu Angeboten Dritter, für deren Inhalte die jeweiligen Anbieter verantwortlich sind.
