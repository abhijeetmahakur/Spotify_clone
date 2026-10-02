# Spotify Web Player Clone

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://abhijeetmahakur.github.io/Spotify_clone/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5 Audio](https://img.shields.io/badge/Audio-HTML5_Audio_API-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/HTMLAudioElement)

A responsive, interactive web music streaming player inspired by Spotify. Features real-time track seeking, synchronized audio playback, animated equalizer waves, dynamic playlist controls, and custom album artwork.

---

## 🚀 Download & Live Demo

### 🌐 1. Play Instantly in Your Browser
Experience music playback directly online without installing anything:  
👉 **[Open Live Spotify Player Demo](https://abhijeetmahakur.github.io/Spotify_clone/)**

### 💻 2. Run Locally on Windows
```powershell
# Clone the repository
git clone https://github.com/abhijeetmahakur/Spotify_clone.git
cd Spotify_clone

# Option A: Start static HTTP server with Python
python -m http.server 8000
# Open http://localhost:8000 in your browser

# Option B: Run with Node.js
npm start
```

---

## 📸 Screenshots & UI Showcase

<!--
  PLACEHOLDER INSTRUCTION:
  1. Open https://abhijeetmahakur.github.io/Spotify_clone/ or http://localhost:8000.
  2. Click Play on any track to trigger the playback bar and animated sound GIF.
  3. Press Win + Shift + S to take a screenshot of the main player and playlist.
  4. Save the screenshot in an `assets/` folder as `player_preview.png`.
-->

| Playlist & Main Player Interface | Bottom Playback Controller |
| :---: | :---: |
| ![Spotify Clone Playlist](https://placehold.co/600x380/121212/1DB954?text=Spotify+Clone+Playlist+Screenshot) | ![Spotify Clone Controls](https://placehold.co/600x380/000000/FFFFFF?text=Spotify+Bottom+Seekbar+%26+Controls) |
| *Track catalogue with album covers, artist names, and play indicators* | *Dynamic scrubber bar, previous/next track buttons, and live title sync* |

---

## ✨ Key Features

- **Smooth Audio Playback Engine:** Powered by native HTML5 `Audio()` API with zero external player libraries.
- **Interactive Scrubber Bar:** Real-time progress bar tracking song duration with click-to-seek scrub functionality.
- **Dynamic Track Switcher:** Next and previous track controls with automated circular looping through the playlist.
- **Visual Playback Feedback:** Animated soundwave GIF indicator and synchronized pause/play icon state updates.
- **Responsive Layout:** Flexbox container styling designed for both desktop and mobile viewports.
- **Bundled Royalty-Free Tracks:** Ships with pre-configured NCS audio samples and album artwork.

---

## 🛠 Tech Stack

| Technology | Category | Role |
| :--- | :--- | :--- |
| **HTML5** | Markup | Semantic markup, audio controls, layout structure |
| **CSS3** | Styling | Dark theme, flexbox, custom scrollbars, range slider accents |
| **JavaScript (ES6+)** | Logic | Audio event listeners (`timeupdate`, `ended`), DOM state manipulation |
| **Font Awesome 5** | Icons | Media controls (play, pause, next, previous) |
| **GitHub Pages** | Hosting | Zero-configuration continuous static deployment |

---

## 📂 Project Structure

```
Spotify_clone/
├── .github/
│   └── workflows/
│       └── deploy-pages.yml     # Automated GitHub Pages CI/CD workflow
├── covers/                      # Album cover artwork (1.jpg to 10.jpg)
├── songs/                       # Bundled royalty-free audio tracks (.mp3)
├── bg.jpg                       # Background banner asset
├── logo.png                     # Spotify brand identity logo
├── playing.gif                  # Animated audio equalizer visualizer
├── index.html                   # Core web structure and layout
├── style.css                    # Theme, styling, and responsive layout
├── script.js                    # Music playback engine and controls
├── package.json                 # Optional npm scripts configuration
├── .gitignore                   # Ignored temporary and IDE files
├── LICENSE                      # MIT License
└── README.md                    # Project documentation
```

---

## 🗺 Roadmap

- [ ] Volume slider and mute toggle controls
- [ ] Shuffle and single-track repeat modes
- [ ] Drag-and-drop custom `.mp3` file player
- [ ] Lyrics display panel synchronized with audio timestamp

---

## 👨‍💻 Author

**Abhijeet Mahakur**
- GitHub: [@abhijeetmahakur](https://github.com/abhijeetmahakur)
- LinkedIn: [Abhijeet Mahakur](https://www.linkedin.com/in/abhijeetmahakur/)
- Location: Bhubaneswar, India

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - Copyright (c) 2026 Abhijeet Mahakur.  
*Disclaimer: This is an educational personal showcase project and is not affiliated with Spotify AB.*