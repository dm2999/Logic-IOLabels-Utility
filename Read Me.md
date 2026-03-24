# Logic IOLabels Utility

A macOS utility for managing **Logic Pro I/O Labels** quickly and safely.

---

## ✨ Features

* 📦 Backup current I/O Labels (plist / CSV)
* 🔄 Recall backups safely
* 📄 Import & export CSV (human-readable)
* 👀 CSV preview before import
* 🧠 Smart rules (auto-handling of Logic label types)
* ⚡ Fast and lightweight

---

## 🛠 How It Works

The app modifies the **Logic Pro I/O Labels plist** while preserving all other settings.

Workflow:

1. Backup current configuration
2. Edit labels via CSV (optional)
3. Recall or import changes

---

## 📁 CSV Format

Human-readable types:

* Mono Input
* Stereo Input
* Mono Output
* Stereo Output
* Bus

Rules:

* If `lname` is not empty → `opt = 4`
* If empty → `opt = 1`

---

## 🚀 Getting Started

1. Download the app
2. Launch it
3. Create a backup
4. Import or edit CSV
5. Recall configuration

---

## ⚠️ Disclaimer

Use at your own risk.
Always create a backup before modifying Logic settings.

---

## 💡 Future Ideas

* Drag & drop CSV
* Auto-detect Logic versions
* UI improvements

---

## 👤 Author

Created by dm2999
