<div align="center">

```
 █████╗ ██████╗      ██████╗ ███████╗███████╗████████╗██╗   ██╗██████╗ ███████╗
██╔══██╗██╔══██╗    ██╔════╝ ██╔════╝██╔════╝╚══██╔══╝██║   ██║██╔══██╗██╔════╝
███████║██████╔╝    ██║  ███╗█████╗  ███████╗   ██║   ██║   ██║██████╔╝█████╗  
██╔══██║██╔═══╝     ██║   ██║██╔══╝  ╚════██║   ██║   ██║   ██║██╔══██╗██╔══╝  
██║  ██║██║         ╚██████╔╝███████╗███████║   ██║   ╚██████╔╝██║  ██║███████╗
╚═╝  ╚═╝╚═╝          ╚═════╝ ╚══════╝╚══════╝   ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚══════╝
███████╗███╗   ██╗ █████╗ ██╗  ██╗███████╗
██╔════╝████╗  ██║██╔══██╗██║ ██╔╝██╔════╝
███████╗██╔██╗ ██║███████║█████╔╝ █████╗  
╚════██║██║╚██╗██║██╔══██║██╔═██╗ ██╔══╝  
███████║██║ ╚████║██║  ██║██║  ██╗███████╗
╚══════╝╚═╝  ╚═══╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
```

# 🐍 AP-GestureSnake

**The Nokia Snake — Reborn with AI Hand Gesture Control**

*Built by **Abhay Pandey** · Powered by TensorFlow.js HandPose*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Mobile Ready](https://img.shields.io/badge/Mobile-Ready-39ff14?style=for-the-badge&logo=android&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

## ⚡ What is AP-GestureSnake?

> A next-gen take on the classic Nokia Snake game — controlled entirely by **AI-powered hand gestures** using your device camera, or by **swiping** on mobile. No buttons. No joystick. Just your hands.

Built with **zero dependencies**, runs 100% in the browser. No install. No backend. No cost.

---

## 🎮 Controls

| Method | How |
|---|---|
| 📱 **Swipe** | Swipe anywhere on screen — works on any phone |
| ☝️ **Hand Gesture** | Point your index finger UP / DOWN / LEFT / RIGHT |
| ⌨️ **Keyboard** | Arrow keys or `W A S D` |

### Hand Gesture Guide
```
  ☝️  Point UP     →  Snake goes UP
  👇  Point DOWN   →  Snake goes DOWN
  👈  Point LEFT   →  Snake goes LEFT
  👉  Point RIGHT  →  Snake goes RIGHT
```

---

## ✨ Features

- 🤖 **Real-time AI Hand Tracking** via TensorFlow.js HandPose model
- 📱 **Fully Mobile Responsive** — swipe-to-move, floating mini camera
- 🖥️ **Desktop Layout** — side-by-side game + gesture camera panel
- 🐍 **Live Hand Skeleton** drawn over camera feed
- 🏆 **Score + Level system** — snake speeds up as you level up
- 💾 **High Score saved** locally in browser
- 🎨 **Retro Nokia green aesthetic** with scanline overlay
- ⚡ **Pure HTML/CSS/JS** — single file, zero build tools

---

## 🚀 Getting Started

### Option 1 — Just open it
```bash
# Download index.html and open in Chrome/Firefox
open index.html
```

### Option 2 — Clone & run locally
```bash
git clone https://github.com/YOUR_USERNAME/AP-GestureSnake.git
cd AP-GestureSnake
# Open index.html in your browser — done!
```

> ⚠️ **Camera/gesture features require HTTPS** when hosted online (works fine on localhost too).

---

## 🌐 Deploy for Free

### Vercel (Recommended)
```bash
npm i -g vercel
vercel --prod
```
Or drag & drop the folder at [vercel.com/new](https://vercel.com/new)

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages → Branch: main → Save**
3. Live at `https://YOUR_USERNAME.github.io/AP-GestureSnake`

### Netlify
Drag & drop `index.html` at [app.netlify.com/drop](https://app.netlify.com/drop)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| `HTML5 Canvas` | Game rendering |
| `Vanilla JavaScript` | Game logic, swipe detection |
| `TensorFlow.js` | ML inference in browser |
| `HandPose Model` | 21-point hand landmark detection |
| `CSS3` | Responsive layout, retro scanline effect |

---

## 📁 Project Structure

```
AP-GestureSnake/
├── index.html        ← Entire game (single file)
├── vercel.json       ← Vercel deployment config
├── .gitignore        ← Git ignore rules
└── README.md         ← You are here
```

---

## 🤝 Contributing

Pull requests are welcome! If you have ideas for new gestures, game modes, or UI improvements:

1. Fork the repo
2. Create your branch: `git checkout -b feature/my-feature`
3. Commit: `git commit -m 'Add my feature'`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📜 License

```
MIT License — © 2026 Abhay Pandey (AP-GestureSnake)
Free to use, modify, and distribute with attribution.
```

---

<div align="center">

**Made with 🖤 by Abhay Pandey**

*If you like this project, drop a ⭐ on GitHub!*

</div>