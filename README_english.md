# Universal Overlay Tool

**Universal Overlay Tool** is a Chrome extension that allows you to create a movable, resizable, and rotatable blur overlay on any webpage – including fullscreen content like videos. It's especially useful for masking or softening specific screen areas (e.g. logos, watermarks, sensitive info) with style.

---

## 🚀 Features

- ✅ Insert a transparent blur overlay on any website
- 🔄 Toggle between **rectangular** and **circular** overlays with a double-click on the slider
- 📏 Resize from all four sides and corners (independently)
- ➕ Drag the overlay anywhere on screen
- 🔁 Rotate the overlay by right-click and holding
- 💾 All settings are saved automatically per shape (rect or round):
  - Position
  - Size
  - Blur strength
  - Rotation angle
- 🖱 UI auto-hides when not hovering
- ❌ Small close button (X) to remove overlay
- 🔄 Double-click on overlay resets size, position, rotation, and blur
- 📚 Keyboard shortcut: `Ctrl + Shift + Y` to insert/remove overlay

---

## 📦 Installation

1. Download this repository or the ZIP file.
2. Open `chrome://extensions/` in your browser.
3. Enable **Developer Mode** (top-right toggle).
4. Click **"Load unpacked"** and select the folder containing this extension.
5. You're ready to go!

---

## 📁 File Structure

```
overlay_plugin/
├── background.js       # Main logic for injecting and managing the overlay
├── icon128.png         # Extension icon
├── manifest.json       # Chrome extension manifest
├── README.md           # This file
```

---

## 🧠 Usage

- Click the extension icon or use `Ctrl+Shift+Y` to activate the overlay.
- Adjust blur strength via the slider.
- Resize the overlay with side or corner handles.
- Right-click and drag to rotate.
- Double-click the **slider** to switch between round and rectangular shape.
- Double-click the **overlay itself** to reset everything.
- Use the ❌ button to close the overlay.

---

## 💡 Notes

- All values are persisted in `localStorage`, so your configuration is remembered per shape type.
- Works in fullscreen mode and on video platforms.

---

## 📃 License

This tool is free to use and modify. No license restrictions apply unless noted otherwise.

---

Enjoy masking like a pro ✨