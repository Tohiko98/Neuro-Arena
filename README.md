# 🧠 NEURO ARENA — Brain Training System v3.0

> A browser-based cognitive training game. No installation, no dependencies — just open and play.

---

## 🎮 Available Games

| Mode | Description | Skill Trained |
|---|---|---|
| 🧠 **Memory** | Memorize number sequences (and letters at higher levels) in limited time | Short-term memory |
| ⚡ **Math Blitz** | Solve math operations against the clock | Calculation speed |
| 🎨 **Stroop Test** | Identify the color of the text, ignoring the written word | Focus, cognitive control |
| 🎯 **Sequences** | Watch and repeat the emoji sequence in the correct order | Procedural memory |

---

## ✨ Features

- **Progressive difficulty** — challenge increases with level: longer sequences, tighter timers
- **Lives & Streak** — 3 lives per session, score multiplier with consecutive correct answers
- **Local leaderboard** — best score per mode saved in the browser
- **Options menu** — sound effects on/off, volume control, name change, data reset
- **Multilingual** — Italian 🇮🇹 and English 🇬🇧
- **Device recognition** — automatically detects if you're playing from a new browser/PC
- **Generative audio** — sounds synthesized via Web Audio API, no external files
- **Zero dependencies** — a single HTML file, works offline

---

## 🚀 How to Play

### Method 1 — Directly in the browser
```
1. Download brain-training.html
2. Open it with any modern browser (Chrome, Firefox, Edge, Safari)
3. Enter your name and start playing
```

### Method 2 — GitHub Pages
```
1. Fork this repository
2. Go to Settings → Pages
3. Select the main branch as source
4. The game will be available at https://<your-username>.github.io/<repo-name>/
```

---

## 📁 Project Structure

```
neuro-arena/
│
├── brain-training.html    # The complete game (HTML + CSS + JS in a single file)
└── README.md              # This file
```

> The project is intentionally contained in a single file for maximum portability.

---

## ⚠️ Important Notes

**Local Leaderboard**
Records are saved in the browser's `localStorage` — each user sees only their own scores. No shared database exists. If you want to share your scores, take a screenshot! 📸

**Compatibility**
Tested on Chrome 120+, Firefox 121+, Edge 120+, Safari 17+.
Requires a browser with **Web Audio API** support for sound effects.

**Privacy**
No data is sent to external servers. Everything stays in your browser.

---

## 🛠️ Future Development (Roadmap)

- [ ] Counter mode — how many correct answers in 60 seconds
- [ ] Online leaderboard (Firebase / Supabase)
- [ ] Full keyboard navigation support
- [ ] Light theme
- [ ] CSS/JS split into separate files
- [ ] PWA (installable as app)

---

## 📄 License

MIT License — free to use, modify and distribute with attribution.

```
Copyright (c) 2025 Anton

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 👤 Author

**Anton** — [github.com/Tohiko98](https://github.com/Tohiko98)
Personal project — built with pure vanilla HTML, CSS and JavaScript.

> *"Train your brain, beat your score."*

---

⭐ If you like the project, leave a star on GitHub! ⭐
