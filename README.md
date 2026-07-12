# ITI21 · Mindmap + Wiedergabe-Training

Interaktive Lern-App für **ITI21 – Netzwerktechnik / IT-Infrastruktur** (Heft 1).
Eine einzige, eigenständige HTML-Datei ohne Abhängigkeiten – einfach öffnen oder online nutzen.

**▶ Live:** https://ayuysal.github.io/iti21-mindmap/

## Funktionen

- **Mindmap-Baum** – 8 farbcodierte Themenzweige (Internet-Aufbau/ISP · Schichtenmodell · OSI · Kapselung/PDUs · TCP/IP · TCP vs. UDP · Netzkomponenten · Netzklassifikation), auf-/zuklappbar, verschiebbarer Canvas, Suche.
- **Karten** mit *In Kürze*, Erklärung und Kernpunkten.
- **Lernmodus** (aktives Erinnern, Leitner-Spaced-Repetition):
  - **Schreib-Modus** – Antwort selbst eintippen; unscharfe Bewertung (Stichwort-Treffer + Tippfehler-Toleranz), Prozent-Score, ab 60 % „Bestanden“.
  - Klassischer Flip-Modus (Antwort aufdecken, selbst bewerten).
- **4 Designs** – Hell · Dunkel · Terminal · Synthwave (oben rechts umschaltbar).
- **Notiz-Editor** (📝) – verschiebbar, Schriftgröße & 3 Schriftarten, Mathe-Zeichen-Palette; in eigenem Fenster auslagerbar und farblich ans Design gekoppelt.

Fortschritt, Design, Notizen und Einstellungen werden lokal im Browser (`localStorage`) gespeichert.

## Nutzung

Online über den Live-Link oben – oder `index.html` lokal im Browser öffnen.

## Weitere Hefte

Die App ist datengetrieben: Für neuen Stoff nur den `const BRANCHES = [ … ]`-Block im `<script>` von `index.html` erweitern/austauschen.
