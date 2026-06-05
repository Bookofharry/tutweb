# 🧵 Social Media Video Scroll Blueprint Website

> **IMPORTANT NOTICE FOR ALL AI AGENTS (Gemini, Claude, Codex, GPT, Cursor, Copilot, etc.)**
> 
> **Repository Purpose:**
> This repository is a static, plain HTML/CSS/JS website designed to be screen-recorded for social media tutorial videos. It is a linear, scroll-only page presenting educational programming content.
> 
> **CRITICAL RULE: DO NOT ADD INTERACTIVE UI ELEMENTS OR MENUS.**
> Future agents must **never** add complex navigation bars, dropdowns, calculators, sidebar tabs, databases, or client-side routers unless explicitly requested by the user. The user scrolls down the page linearly to record contents. All information must be fully pre-rendered, static, and visible at all times.

---

## 🎨 Visual Design Guidelines

For any future text changes or layout edits, you **must** adhere strictly to the visual guidelines below:

### 1. Color Palette (Dark Navy & Neon Accents)
- **Background**: Deep Navy `#020617` / `#050c21`.
- **Card Background**: `#0b1329`.
- **Accents**: Cyan (`#00b0ff`), Purple (`#d500f9`), Emerald (`#00e676`), Rose Red (`#ff3366`), and Deep Black (`#000000`).

### 2. High-Contrast Border Scheme
Every content card must use a thick `4px solid` border to guide the eye on social feeds. Use the following border utility classes:
- `card-border-black`: High contrast dark boundary.
- `card-border-purple`: Vibrant purple border.
- `card-border-green`: Positive leverage/success metrics.
- `card-border-red`: Warnings, cautions, or old mindsets.
- `card-border-blue`: Primary information / summary details.

### 3. Screen-Recording Typography Scale
All typography must remain huge, legible, and clear on mobile phones without zooming:
- **Card Titles**: `font-size: clamp(3rem, 7vw, 4.5rem)` with explicit line heights of `1.15`. Use `<br>` tags to control line wrapping for short, punchy video hooks.
- **Card Body**: `font-size: clamp(1.4rem, 3.5vw, 1.85rem)`.
- **List Headers**: `font-size: clamp(1.4rem, 3.8vw, 1.95rem)`.
- **List Details**: `font-size: clamp(1.2rem, 3vw, 1.55rem)`.

---

## 📁 Repository Structure

- `index.html` — The structured semantic layout, containing sequential thread sections.
- `style.css` — Custom properties, radial blur orbs, and utility colors.
- `app.js` — Minimal script module. Keep empty or clean of event listeners.
- `README.md` — This instruction manual.

---

## 🚀 Running the Local Server

To preview changes or record the site locally, spin up a simple static HTTP server:

```bash
# Start the server on port 8080
npx http-server -p 8080
```

Open your browser to: **`http://localhost:8080`**
