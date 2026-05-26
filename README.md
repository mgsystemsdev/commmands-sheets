# Keyboard Command Deck

An interactive, searchable reference for navigating macOS, VS Code, and Chrome entirely by keyboard. Single static `index.html` — no build step, no dependencies.

## Features
- 🔍 **Live search** — type to filter every shortcut (press `/` to focus, `Esc` to clear)
- 🎛️ **Filter by app** — macOS, Chrome, VS Code (incl. terminal), Text, GitHub, Setup
- 📋 **Click to copy** — hover any card and copy the shortcut
- 🌗 **Light / dark theme** toggle
- 📱 Responsive — works on phone, laptop, and big monitors

## Deploy to GitHub Pages

1. Create a new repository (e.g. `command-deck`).
2. Add `index.html` to the root of the repo and push:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Keyboard Command Deck"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/command-deck.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source → Deploy from a branch**, pick `main` / `root`, Save.
4. Your site goes live at `https://YOUR-USERNAME.github.io/command-deck/` within a minute or two.

> Tip: to serve it at `https://YOUR-USERNAME.github.io/` directly, name the repo `YOUR-USERNAME.github.io`.

## Edit the shortcuts
All content lives in the `SECTIONS` array near the top of the `<script>` block in `index.html`. Add or change cards there — no other edits needed.
