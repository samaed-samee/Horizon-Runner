# 🏃 Horizon Runner: Urban Parkour

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen.svg?style=flat-square)
![Author](https://img.shields.io/badge/author-samaed--samee-orange.svg?style=flat-square)
![Stars](https://img.shields.io/github/stars/samaed-samee/Horizon-Runner?style=flat-square)

> A high-octane, atmospheric endless runner set in a procedural urban landscape. Experience the thrill of parkour with dynamic weather, day-night cycles, and immersive audio.

## 🎮 Overview

**Horizon Runner** is a browser-based side-scrolling platformer where you control a parkour runner navigating a never-ending city skyline. Master the art of momentum, manage your stamina, and adapt to changing weather conditions as you race against your own limits.

Built with vanilla **JavaScript** and **HTML5 Canvas**, styled with **TailwindCSS**.

## ✨ Key Features

-   **🏙️ Procedural Generation**: No two runs are the same. Platforms and city skylines are generated on the fly.
-   **🌦️ Dynamic Weather System**: Experience realistic rain storms with thunder and lightning effects that intensify over time.
-   **🌓 Day/Night Cycle**: Watch the sun set and rise as you run, with beautiful gradient sky transitions.
-   **🔊 Immersive Audio**: Procedural sound generation for footsteps, rain, thunder, and jump effects using the Web Audio API.
-   **⚡ Stamina Mechanics**: Manage your energy for dashes and sustained sprints.
-   **📱 Mobile Responsive**: Fully playable on desktop and touch devices.

## 🕹️ Controls

| Action | Desktop (Keyboard) | Mobile (Touch) |
| :--- | :--- | :--- |
| **Jump** | `SPACE` | Tap **Left** side of screen |
| **Dash** | `SHIFT` | Tap **Right** side of screen |

> **Pro Tip:** Time your dashes to clear large gaps, but watch your stamina bar!

## 🚀 How to Play

1.  **Start the Game**: Click "Begin Run" on the main menu.
2.  **Keep Running**: Avoid falling off buildings.
3.  **Score Points**: Your distance roughly equates to your score. Aim for a new high score!
4.  **Weather the Storm**: Visual visibility changes with rain and night time – stay sharp.

## 🛠️ Tech Stack

<div align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</div>

-   **Rendering Engine**: HTML5 Canvas 2D API for high-performance rendering.
-   **Physics**: Custom-built 2D physics engine with gravity and collision detection.
-   **Audio Synthesis**: Web Audio API for real-time procedural soundscapes (no MP3/WAV files).
-   **UI/UX**: Responsive design powered by TailwindCSS and CSS transitions.

## ⚡ Performance & Optimization

-   **Offscreen Cleanup**: Platforms and buildings are dynamically removed from memory once they move off-screen to ensure long-term stability.
-   **Procedural Audio**: Using the Web Audio API instead of static files reduces initial load time and allows for infinitely variable sound patterns (like varying rain intensity).
-   **Canvas Optimization**: Minimal overdraw and efficient clearRect loops maintain a steady 60 FPS on most modern hardware.

## 🗺️ Roadmap

- [ ] **Character Skins**: Unlockable outfits based on distance achieved.
- [ ] **New Environments**: Cyberpunk rooftops, industrial zones, and forest parkour.
- [ ] **Global Leaderboard**: Save and compete with runners worldwide.
- [ ] **Power-ups**: Magnets for score boosters or slow-motion "focus" mode.

## 📦 Installation & Setup

No build process required! This game runs directly in the browser.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/samaed-samee/Horizon-Runner.git
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd Horizon-Runner
    ```
3.  **Run the game:**
    -   Simply open `index.html` in your favorite web browser.
    -   *Optional*: Use a local server like `Live Server` for the best experience.

## 🤝 Contributing

Contributions are welcome!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 👤 Author

**samaed-samee**
- GitHub: [@samaed-samee](https://github.com/samaed-samee)

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Made with ❤️ and code.*

