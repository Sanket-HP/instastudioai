# 🎬 Insta Studio Pro — Frontend AI Reel Generator

**Insta Studio Pro** is a modern, frontend-only AI Reel Studio that enables creators to design, narrate, visualize, and export short-form vertical videos (Instagram Reels, YouTube Shorts) directly from the browser.

This project is built with **zero backend** and follows a **Bring-Your-Own-API-Key (BYOK)** model for full transparency and user control.

🔗 Live Demo: https://instastudioai.vercel.app/

---

## ✨ Features

- 🎥 End-to-end reel creation: **Blueprint → Narration → Synthesis**
- 🧠 AI-powered multi-scene storyboarding
- 🗣️ AI voice narration with language & voice selection
- 🖼️ AI-generated visuals or user-uploaded photos
- ✏️ Live scene editor (edit narration & prompts)
- 🎶 Music sync with volume control
- 📱 9:16 vertical video export
- 🔐 Google Authentication (client-side only)
- 🚫 No backend, no servers, no databases

---

## 🧩 Project Philosophy

Insta Studio Pro is intentionally designed as a **client-side application**.

- No server infrastructure
- No stored user data
- No API keys collected or proxied
- All processing happens inside the browser

This makes the tool lightweight, transparent, and ideal for:
- Frontend experimentation
- Hackathons & demos
- Creator tools
- Indie & BYO-key workflows

---

## 🔑 API Key Model (BYOK)

This project uses a **Bring-Your-Own-API-Key** approach.

- Users enter their own AI API key
- The key is used only in-session
- The key is automatically cleared after synthesis
- The project owner never accesses or stores API keys

> ⚠️ Users are responsible for their own API usage, quotas, and billing.

---

## 🛠️ Tech Stack

**Frontend Only**
- HTML5
- CSS3
- Tailwind CSS
- Vanilla JavaScript
- Canvas API
- MediaRecorder API
- Web Audio API
- Firebase Authentication (Google Sign-In only)

No backend frameworks or server-side code are used.

---

## 🎨 Core Capabilities

### 🧠 Storyboard Generator
- Automatically generates a structured multi-scene reel
- Each scene includes narration and visual intent

### ✏️ Live Scene Editor
- Edit narration text
- Edit visual prompts
- No regeneration required

### 🎥 Video Export Engine
- Canvas-based rendering
- Ken Burns visual effect
- Music + narration mixing
- VP8 WebM export for broad compatibility

---

## 🔐 Authentication

- Google Sign-In via Firebase Authentication
- Used only for:
  - UI access control
  - Profile display
- No content or projects are stored remotely

---

## ⚠️ Limitations

- No API usage control (frontend-only by design)
- No server-side rendering
- Export duration depends on browser memory
- Some AI providers may change browser support over time

These are known and accepted trade-offs of a no-backend architecture.

---

## 📦 Ideal Use Cases

- Hackathons & project demos
- Frontend architecture showcases
- Creator tools for power users
- Educational & experimental AI projects
- White-label UI studios

---

## 📜 License & Ownership

**© 2025 — All Rights Reserved**

**Author & Project Owner:**  
**Sanket Sarjerao Patil**

- Concept & Product Design: Sanket Sarjerao Patil  
- Frontend Architecture & Development: Sanket Sarjerao Patil  
- UI / UX / Logic: Sanket Sarjerao Patil  

No part of this project may be copied, redistributed, or commercialized without explicit permission from the author.

---

## 🚀 Final Note

Insta Studio Pro demonstrates how powerful modern browsers have become when combined with thoughtful UX and frontend engineering.

This project intentionally avoids backend complexity to remain:
- Transparent
- Lightweight
- User-controlled

---

⭐ If you like this project, consider giving it a star on GitHub.
