# TIME-BOOKLET

Dieses kleine Tool hilft dir, deine Arbeitszeit in der SAP-Übersicht besser im Blick zu behalten. Es zeigt dir, wann du gehen darfst und ab wann "Hybrid" (Homeoffice) möglich ist.

## Versionierung
* **Version 1.5.1 (Aktuell)**: Bugfix für das Overlay – Detail-Statistiken aktualisieren sich nun bei jedem Klick live.
* **Version 1.5.0**: 
    * Interaktives Overlay mit Klick-Funktion für Detail-Infos.
    * Visueller Ladebalken am unteren Rand des Overlays.
    * Weiße Markierung im Ladebalken zeigt die Hybrid-Schwelle.
    * Zweiter Live-Counter für die verbleibende Zeit bis zum Hybrid-Status.
* **Version 1.1.0**: Umstellung der Standard-Sollzeit auf 7 Stunden (420 Min) und Entfernung des Zeitpuffers.
* **Version 1.0.0**: Basis-Version mit 8 Stunden (480 Min), Hybrid-Check und Live-Countdown.

## Was das Tool macht
* **Arbeitszeit:** Rechnet aus, wie lange du heute schon da bist.
* **Pausen:** Prüft, ob du die 50 Min. Mindestpause erreicht hast.
* **Hybrid-Dashboard:** Zeigt dir im Overlay die Zeit bis zum möglichen Wechsel ins Homeoffice (75%-Regel).
* **Live-Fortschritt:** Ein visueller Balken und ein Countdown zeigen dir sekundengenau den Weg zum Feierabend.
* **Interaktivität:** Klicke auf das Overlay am Bildschirmrand, um die detaillierten Statistiken jederzeit **live** aufzurufen.

## So installierst du es
1. Erstelle ein neues **Lesezeichen** (Bookmark) in deinem Browser (Chrome).
2. Gib ihm einen Namen, z. B. `🕒 Zeit-Check`.
3. Kopiere den kompletten JavaScript-Code und füge ihn im Feld **URL** bzw. **Adresse** ein.
4. Speichern – fertig!

## So benutzt du es
1. Öffne deine Zeiterfassungs-Seite im Browser.
2. Klicke auf das Lesezeichen in deiner Leiste.
3. Sofort erscheint die Übersicht und das interaktive Overlay startet unten rechts.

## Die Regeln im Code
* **Soll:** 7 Stunden (420 Min) – *Individuell im Code anpassbar.*
* **Pause:** Mindestens 50 Min. (Differenz wird bei Unterschreitung automatisch addiert).
* **Hybrid:** Exakt 75% der Sollarbeitszeit.

---
*Privates Tool – Nutzung auf eigene Verantwortung.*
