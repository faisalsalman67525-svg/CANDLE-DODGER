# 📉 CANDLE DODGER

> One tap. One chart. Don't get liquidated.

**Candle Dodger** is a fast, addictive one-tap mini game that runs in your browser. A glowing ball flies through a scrolling trading chart: dodge the red candles, collect the green ones, and build the biggest combo you can.

Single HTML file. No libraries. No downloads. Works on phone and desktop.

👉 **[Play Now](https://YOUR-USERNAME.github.io/candle-dodger/)**

---

## 🎮 How to Play

- **Hold** the screen (or mouse / spacebar) → the ball goes **up**
- **Release** → the ball **falls**
- Avoid the **red candles** 🔴
- Collect the **green candles** 🟢 to build your combo multiplier
- Pass close to a red candle for a **CLOSE CALL** bonus

A run lasts 20–60 seconds. Tap once and you're back in. No menus, no waiting.

---

## ✨ Features

- **One-tap controls**: learn it in 3 seconds
- **Combo system**: x2, x3, x4... the riskier you play, the more you score
- **Near-miss bonus** with slow-motion flash and screen shake
- **Power-ups**: Bull Run (invincible), Slow Mo, x2 Score
- **Daily Challenge**: the same seeded candle pattern for everyone, every day
- **Unlockable skins**: Bronze, Silver, Gold, Diamond, Rainbow
- **Ghost line** showing where your previous best run ended
- **Procedural sound effects** (Web Audio API) with a mute button
- **Share button** to challenge your friends
- Saves your best score and skins in `localStorage`
- Smooth 60fps with particles, glow and screen shake

---

## 🚀 Run Locally

```bash
git clone https://github.com/YOUR-USERNAME/candle-dodger.git
cd candle-dodger
```

Then simply open `index.html` in your browser. That's it, no build step.

---

## 🌐 Deploy on GitHub Pages (Free)

1. Make sure the game file is named **`index.html`** in the repo root
2. Go to your repo → **Settings** → **Pages**
3. Under **Source**, choose **Deploy from a branch**
4. Select **`main`** branch and **`/ (root)`** folder, then **Save**
5. After a minute, your game will be live at:
   `https://YOUR-USERNAME.github.io/candle-dodger/`

---

## ⚙️ Customize

All the important settings are in the `CONFIG` object at the top of the code:

| Setting | What it does |
|---|---|
| `speed` | Starting scroll speed |
| `rampRate` | How fast difficulty increases |
| `gapSize` | Gap between red candles |
| `gravity` | How fast the ball falls |
| `colors` | Game color palette |

Tweak the values, refresh the page, and see the difference.

---

## 🗂 Project Structure

```
candle-dodger/
├── index.html     # The whole game (HTML + CSS + JS)
└── README.md      # You are here
```

---

## 🛠 Built With

- HTML5 Canvas
- Vanilla JavaScript
- Web Audio API
- Web Share API

---

## 🤝 Contributing

Ideas, bug reports and pull requests are welcome.

1. Fork the repo
2. Create your branch: `git checkout -b feature/my-idea`
3. Commit your changes: `git commit -m "Add my idea"`
4. Push: `git push origin feature/my-idea`
5. Open a Pull Request

---

## 📸 Screenshots

<!-- Add your screenshots or a gameplay GIF here -->
<!-- ![Gameplay](screenshots/gameplay.gif) -->

---

## 📄 License

This project is licensed under the MIT License. Feel free to use, modify and share it.

---

## 💬 Share Your Score

Beat your friends and post your score:

> I survived 47 candles in CANDLE DODGER 📉 Can you beat me? 👉 https://YOUR-USERNAME.github.io/candle-dodger/

**Made with ❤️ by YOUR-NAME**
