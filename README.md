# 💻 Emo OS Premium Edition

Welcome to **Emo OS**, a fully customized, ultra-modern, dark-themed, and glassmorphic operating system running entirely in your browser! Crafted and conceptualized by **Mohit**.

![Emo OS Wallpaper](./public/img/wallpaper/default/img0.jpg)

---

## 🌟 Overview

Emo OS is an interactive, browser-based operating system designed for maximum aesthetic appeal. Built with a dark neo-cyberpunk vibe, it features glowing neon accents, functional widgets, a hacker-style terminal, and a suite of customized web applications seamlessly integrated into the desktop experience.

Whether you're using it as a sleek personal portfolio or just to experience a cool customized environment, Emo OS pushes the boundaries of what a web application can look and feel like.

## 🚀 Key Features

### ✨ UI & Aesthetics
- **Neon Glow & Glassmorphism:** Experience beautiful blur effects on the Start Menu and Taskbar, enhanced with a pulsing neon purple glow (`#8b5cf6`).
- **Custom Cyberpunk Cursor:** The entire OS utilizes a custom neon-purple crosshair/pointer, setting it apart from standard environments.
- **Boot Animation:** A custom startup screen with a glowing "Emo OS" logo welcomes you upon boot.
- **Dynamic 8K Wallpapers:** Easily switchable high-resolution backgrounds.

### 💻 Emo Terminal (Hacker Console)
The built-in terminal is not just for show—it comes packed with features:
- **Custom Prompt:** Runs as `mohit@Emo-OS:~$` for an authentic hacker feel.
- **`neofetch`:** Type `neofetch` to see a beautiful custom ASCII art logo and your system specifications.
- **`play music`:** Type this command to automatically launch your music player!
- **`systeminfo`:** Check out the tailored Emo OS hardware/software properties.

### 📱 Integrated Applications
- **EMOVibes:** A fully integrated music platform directly accessible from the desktop.
- **Emo-Links:** Your customized link tree and portfolio portal.
- **Emo-Learners:** Access learning resources via a dedicated shortcut.
- **Emo-Games:** Built-in games! Includes a fully playable version of 2048 (`https://emo-games.vercel.app/`).

---

## 📸 Preview

Here is a glimpse of the beautiful Emo OS interface:

| Desktop & Widgets | Start Menu |
| :---: | :---: |
| ![Desktop View](./public/img/screenshots/desktop.png) | ![Start Menu](./public/img/screenshots/startmenu.png) |
| **File Explorer** | **Emo Terminal (Hacker Console)** |
| ![File Explorer](./public/img/screenshots/explorer.png) | ![Terminal](./public/img/screenshots/terminal.png) |

---

## 🛠️ Tech Stack

- **Frontend Framework:** React 18
- **State Management:** Redux
- **Styling:** Tailwind CSS & SCSS (Vanilla CSS for custom animations)
- **Bundler:** Vite

---

## 💻 Quick Start Guide

To run Emo OS locally on your machine:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Emomohit/EmoOS.git
   ```

2. **Navigate into the project directory:**
   ```bash
   cd EmoOS
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   # or
   npm start
   ```

Your personalized Emo OS will now be running at `http://localhost:5173`.

---

## 🔧 Customization Guide

Want to tweak Emo OS further? Here’s where to look:

- **Desktop Apps & Shortcuts:** Edit `src/utils/apps.js` and `src/utils/index.js`.
- **Terminal Commands:** Add or edit commands in `src/containers/applications/apps/terminal.jsx`.
- **Global Styles (Cursor, Fonts):** Modify `src/index.css`.
- **Wallpapers:** Add new images to `public/img/wallpaper/` and update `src/reducers/wallpaper.js`.
- **Start Menu & Taskbar Glowing Effects:** Tweak shadows and colors in `src/components/taskbar/taskbar.scss` and `src/components/start/startmenu.scss`.

---

## 🌐 Deployment

Emo OS is fully optimized to be hosted as a static site. You can easily host this project on [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or GitHub Pages for free!

1. Create a new project on Vercel.
2. Link this GitHub repository.
3. Vercel will automatically detect the Vite build settings (`npm run build`).
4. Deploy and access Emo OS from anywhere!

---
*Developed with 💜 by Mohit.*

 
<!-- Minor tweak 1 -->
<!-- Minor tweak 2 -->
<!-- Minor tweak 3 -->
<!-- Minor tweak 4 -->
<!-- Minor tweak 5 -->
<!-- Minor tweak 6 -->
<!-- Minor tweak 7 -->
<!-- Minor tweak 8 -->
<!-- Minor tweak 9 -->
<!-- Minor tweak 10 -->
