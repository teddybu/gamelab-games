# GameLab AI – Eigene Videospiele durch Vibecoding

**AG am Max-Planck-Gymnasium Berlin | Schuljahr 2026/27**

> Du beschreibst deine Spielidee – die KI schreibt den Code.
> Du bist der Game Designer. Die KI ist dein Entwickler-Team.

---

## Was ist das hier?

Dieses Repository enthält die **GameLab Spielewelt** – die Startseite, auf der alle Browserspiele unserer AG gesammelt und verlinkt werden.

In der AG **GameLab AI** entwickeln Schüler\*innen der Jahrgänge 7 und 8 eigene Videospiele – **ohne klassisch programmieren zu lernen**.

Der Ansatz heißt **Vibecoding**:

1. Du beschreibst dein Spiel in natürlicher Sprache.
2. Eine KI generiert den funktionierenden Code.
3. Du testest, findest Fehler und gibst der KI neue Anweisungen.
4. Dein Spiel läuft – und du hast es selbst „gebaut“.

---

## Spiele live spielen

Alle Spiele sind direkt im Browser spielbar – **kein Download, kein Setup:**

**[teddybu.github.io/gamelab-games](https://teddybu.github.io/gamelab-games/)**

---

## Tech-Stack

| Tool | Zweck |
|------|-------|
| **Visual Studio Code** | Code-Editor mit KI-Integration |
| **GitHub Copilot** | KI-Code-Assistent (Cloud) |
| **HTML5 / CSS / JavaScript** | Startseite und Spiele (vom KI-Agenten geschrieben) |
| **GitHub Pages** | Hosting & Live-Präsentation der Spiele |
| **Git & GitHub** | Versionskontrolle & Deployment |

Die Seite ist eine **rein statische Website**: kein Build-Schritt, keine Frameworks, keine zusätzlichen Abhängigkeiten.

---

## Projektstruktur

```
gamelab-games/
├── index.html   ← Startseite „GameLab Spielewelt“ mit allen Spielkarten
├── style.css    ← Gemeinsames Design inkl. Farbklassen für die Karten
└── README.md    ← Diese Datei
```

---

## Lokal ansehen

1. Repository herunterladen oder klonen:
   ```bash
   git clone https://github.com/teddybu/gamelab-games.git
   ```
2. `index.html` im Browser öffnen – fertig.

---

## Ein neues Spiel hinzufügen

1. In `index.html` innerhalb von `.game-grid` eine vorhandene `game-card` kopieren.
2. In der Kopie anpassen:
   - **Link** zum Spiel
   - **Spieltitel**
   - **Name** der Person, die das Spiel erstellt hat
   - **Nummer** der Karte
3. Optional eine Farbe wählen: Die Farbklassen der Karten in `style.css` können wiederverwendet oder um eigene Farben erweitert werden.
4. Änderungen committen und pushen – GitHub Pages aktualisiert die Live-Seite automatisch nach kurzer Zeit.

---

## Veröffentlichung

Die Seite wird über **GitHub Pages** direkt aus dem `main`-Branch veröffentlicht:
[https://teddybu.github.io/gamelab-games/](https://teddybu.github.io/gamelab-games/)
