
# 🔲🔵 Custom Overlay Extension – Blur, Shape, Rotate & More

Diese Chrome-Erweiterung fügt ein **anpassbares Overlay** auf jeder beliebigen Webseite ein. Das Overlay kann in Form, Position, Größe, Transparenz und Weichzeichner angepasst werden und ist ideal für visuelle Fokusbereiche, Diskretion oder Design-Tools.

---

## 🧩 Funktionen im Überblick

### ✅ **Form umschaltbar**
- Standardmäßig rechteckig.
- Per **Doppelklick auf den Blur-Slider** kannst du zwischen **rechteckiger** und **runder** Form (Kreis oder Ellipse) umschalten.
- Jede Form speichert ihre eigene Position, Größe, Blur-Intensität und Rotation separat.

---

### 🎯 **Größe und Form anpassbar**
- Ziehe das Overlay an **jeder Seite** oder **Ecke**, um die Größe **einzeln** zu verändern – auch asymmetrisch.
- Das runde Overlay kann dadurch **zur Ellipse** geformt werden.
- Rechteckige Overlays lassen sich in **beliebige Proportionen** bringen.

---

### ✋ **Verschiebbar**
- **Linksklick und Ziehen** auf das Overlay verschiebt es frei auf dem Bildschirm.
- Position wird für jede Form automatisch gespeichert (auch nach einem Neustart des Browsers).

---

### 🔁 **Rotation**
- **Rechtsklick halten** auf das Overlay und Maus im Kreis bewegen → dreht das Overlay um die eigene Achse.
- Rotation wird gespeichert und beibehalten.

---

### 🔄 **Reset-Funktion**
- **Doppelklick auf das Overlay** setzt alle Werte zurück:
  - Standardgröße
  - Position mittig
  - 0° Rotation
  - Maximaler Blur
  - Originalform (runde Form bleibt rund)

---

### 🌫️ **Blur anpassbar**
- **Slider** in der Mitte des Overlays regelt die Stärke des Unschärfeeffekts (0–100%).
- Der Blur wirkt durch CSS `backdrop-filter` und erzeugt einen hochwertigen Weichzeichner über den Hintergrund.

---

### 👁️‍🗨️ **Hover-Steuerung**
- **UI-Elemente (Slider, Schließen-Button)** werden **nur sichtbar**, wenn die Maus über dem Overlay schwebt.
- Overlay bleibt ansonsten clean und unauffällig.

---

### ❌ **Overlay entfernen**
- Das kleine **"X"** neben dem Slider entfernt das Overlay komplett.

---

## 💾 Speicherung
Alle Einstellungen werden lokal im `localStorage` des Browsers gespeichert:
- Für **runde** und **rechteckige** Form getrennt:
  - Position
  - Größe
  - Blur-Wert
  - Rotation

---

## 🚀 Bedienung – Kurzübersicht

| Aktion                         | Ergebnis                                    |
|-------------------------------|---------------------------------------------|
| Doppelklick auf Blur-Slider   | Form umschalten (rund/rechteckig)           |
| Doppelklick auf Overlay       | Alle Einstellungen zurücksetzen             |
| Linksklick & Ziehen           | Overlay verschieben                         |
| Rechtsklick & Ziehen          | Overlay rotieren                            |
| An Seiten/Ecken ziehen        | Größe und Form anpassen                     |
| Hover                         | UI (Slider, Close) wird sichtbar            |
| Klick auf "X"                 | Overlay schließen                           |

---

## 🛠️ Installation & Nutzung

1. Entpacke das ZIP mit `manifest.json`, `background.js` und `icon.png`
2. Gehe in Chrome zu `chrome://extensions`
3. Aktiviere den **Entwicklermodus**
4. Klicke auf **"Entpackte Erweiterung laden"** und wähle deinen Ordner
5. Erweiterung erscheint im Toolbar-Menü
6. **Klick auf das Icon** fügt das Overlay ein

---

## 🧪 Anwendungsmöglichkeiten

- Unwichtige Inhalte ausblenden (z. B. Werbung, Chat, Sidebar)
- Visueller Fokus in Web-Apps oder Präsentationen
- Videos oder Bilder dezent weichzeichnen
- Inhalte anonymisieren (z. B. für Screenshots)
- UX-Design-Experimente oder visuelle Marker

---

## 📄 Lizenz

MIT License – Frei zur privaten und kommerziellen Nutzung.
