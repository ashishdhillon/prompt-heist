# Prompt Heist 🕵️

> **[🎮 Play it live](https://ashishdhillon.github.io/prompt-heist/)**

A tiny browser game: eight guards each protect a secret word. Talk them into leaking it, then type the password to unlock the next level. Fewer messages and hints means a better rank.

**Two ways to play:** the 8-level Campaign, and the **Daily Heist**: one guard and one secret word a day, the same for everybody, with a streak counter and a shareable result card. (The daily guard is picked from the date on your device, so there is no server.)

No backend, no API key, no build step. Open `index.html`, or host the folder on GitHub Pages.

The guards are rule-based, not real LLMs. Each one models a real prompt-injection weakness (trusting authority, blocklists, output filters, role-play, translation, emotional pressure, autocomplete, and layered defences), so it is a playful way to learn why those defences fail.

MIT licensed.
