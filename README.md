# 🎵 AetherAudio — Studio-Grade Music Streaming Web App

A modern, responsive, high-fidelity music streaming website interface crafted purely with **semantic HTML5** and **modern CSS3**. Inspired by Spotify, Tidal, and Apple Music with a dark-mode cyberpunk aesthetic, glassmorphic surfaces, and neon accents.

🔗 **GitHub Repository:** [https://github.com/balamanidharyella-afk/music-streaming-website](https://github.com/balamanidharyella-afk/music-streaming-website)  
🌐 **Live Demo (GitHub Pages):** [https://balamanidharyella-afk.github.io/music-streaming-website/](https://balamanidharyella-afk.github.io/music-streaming-website/)

![AetherAudio Preview](https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?auto=format&fit=crop&w=1200&q=80)

---

## ✨ Features & Sections

### 1. 🧭 Sidebar Navigation & Top Bar
- **Fixed Sidebar**:
  - Brand header with soundwave logo and glowing gradient badge.
  - Quick navigation: **Home**, **Browse**, **Playlists**, and **Library**.
  - Pinned playlists, Liked Songs counter badge, and Hi-Fi "AetherAudio Studio" promotion card.
  - Fully responsive: transforms into a slide-over mobile drawer via a pure CSS checkbox trigger.
- **Top Bar**:
  - Blurred glassmorphism header with history navigation buttons (`<` and `>`).
  - Search input with search icon and keyboard shortcut indicator (`⌘K`).
  - Notification bell with live dot, "Get VIP" button, and user profile avatar with online presence indicator.

### 2. 🌟 Featured Hero Banner
- Trending album showcase featuring *"Neon Odyssey Deluxe"* by Aura Nova & The Synth Syndicate.
- High-res artwork with interactive 3D vinyl record slide-out animation on hover.
- Live animated pulse tag ("Trending Album • Dolby Atmos").
- Action buttons: Glowing "Play Now", "Save to Library", and extra options.

### 3. 👥 Artists & 💽 Albums
- **Popular Artists**: Circular avatar cards with neon glow hover effects, verified artist badges, listener counts, and floating play buttons.
- **Trending Albums**: Square album covers with Hi-Res / Spatial Audio badges, release year, song count, and hover overlay play triggers.

### 4. 🔀 Playlists & ⏱️ Recently Played
- **Curated Playlists**: Card grids with tailored color-themed badges (*Cyberpunk Coding*, *Midnight Velvet Neo-Soul*, *Electric Club Peak Time*, *Rainy City Coffee Shop*).
- **Recently Played Row**: Quick-access compact cards with live animated sound equalizer bars and quick play buttons.

### 5. 🎧 Popular Tracks Tracklist
- Structured tracklist table featuring song rank, album artwork thumbnail, title, artist, explicit content badge (`E`), album name, play count, duration, and actions.
- Currently playing song row with neon green highlight and dancing equalizer wave bars.
- Interactive pure CSS favorite heart toggles and hover play/pause buttons.

### 6. 🎚️ Fixed Bottom Music Player Bar
- **Now Playing Area**: Track thumbnail, song title with "MASTER" badge, artist name, and live streaming dot.
- **Playback Controls**:
  - Shuffle, Previous, Play/Pause, Next, and Repeat buttons.
  - Interactive pure CSS Play/Pause toggle state.
  - Interactive Shuffle and Repeat toggle states with glowing active indicators.
- **Timeline & Progress Bar**: Current time and total duration timestamps with a custom neon slider track and glowing progress fill.
- **Audio Utilities**: Lyrics, Queue, Device Connect, Mute toggle button, and custom styled volume slider.
- **Mobile Mode**: Adapts into a streamlined mini player with an integrated top progress line, accompanied by a dedicated bottom navigation bar.

---

## 🎨 Design & Aesthetic Highlights

- **Dark-Mode Palette**: Deep charcoal and black foundation (`#08090c`, `#0f1117`, `#161b26`).
- **Neon Accents**: Electric emerald (`#00f59b`), Cyber violet (`#9d4edd`), and Electric cyan (`#00d4ff`).
- **Glassmorphism**: Translucent card elevations with `backdrop-filter: blur(20px)` and subtle borders.
- **Zero JavaScript Required**: Interactive states (menus, drawers, toggles, play/pause switches, heart favorites, mute buttons) are executed purely using CSS `:checked`, `:hover`, and sibling combinators.
- **Typography**: Clean, readable sans-serif powered by Google Font *Plus Jakarta Sans*.

---

## 📱 Fully Responsive Breakpoints

| Device | Breakpoint | Adaptations |
| :--- | :--- | :--- |
| **Desktop / Ultrawide** | `> 1200px` | Full multi-column grid, persistent 260px sidebar, complete tracklist table, full bottom player bar. |
| **Laptop** | `992px – 1200px` | 3–4 card columns, scaled down hero banner and vinyl animation. |
| **Tablet** | `768px – 991px` | Compact sidebar, single-column hero card, hidden non-critical table columns (album, play count). |
| **Mobile** | `< 768px` | Off-canvas drawer menu with hamburger toggle, compact mobile player, and fixed mobile bottom navigation bar. |
| **Small Phone** | `< 480px` | 2-column cards, optimized compact headers and touch targets. |

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser:

```bash
# Option 1: Directly open the file in your default browser (macOS/Linux/Windows)
start index.html   # On Windows
open index.html    # On macOS
xdg-open index.html # On Linux

# Option 2: Run a local static server
npx serve .
# or
python -m http.server 3000
```

---

## 🛠️ Built With

- **HTML5**: Semantic tags (`<header>`, `<nav>`, `<aside>`, `<main>`, `<section>`, `<table>`, `<footer>`)
- **CSS3**: CSS Grid, Flexbox, Custom Properties (`:root`), Keyframe Animations, Glassmorphism
- **SVGs**: Crisp, lightweight inline vector icons

---

## 📄 License

MIT License. Free to use for personal and commercial projects.
