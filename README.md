# Prompt Heist 🕵️

> **[🎮 Play it live](https://ashishdhillon.github.io/prompt-heist/)**

A tiny browser game: five guards each protect a secret word. Talk them into leaking it, then type the password to unlock the next level. Fewer messages and hints means a better rank.

No backend, no API key, no build step. Open `index.html`, or host the folder on GitHub Pages.

The guards are rule-based, not real LLMs. Each one models a real prompt-injection weakness (trusting authority, blocklists, output filters, role-play, and layered defences), so it is a playful way to learn why those defences fail.

MIT licensed.
