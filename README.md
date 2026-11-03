# Aishu – personal voice assistant

A single-file website. Tap the lamp once, then say **"Hey Aishu"** followed by a command.

- Works in Chrome, Edge and Safari (needs microphone access, and HTTPS or localhost)
- English and Telugu
- Built in: time, date, jokes, timers, math, notes, "search …", "play …", "open youtube"
- Optional AI answers: add a Claude, ChatGPT or Gemini key in Settings (stored only in your browser)

## Deploy (GitHub Pages)

```bash
git init -b main
git add .
git commit -m "Aishu assistant"
git remote add origin https://github.com/<your-username>/aishu.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Source: GitHub Actions**. Every push to `main` redeploys.
Your site will be at `https://<your-username>.github.io/aishu/`.

Never hardcode an API key in `index.html` – anyone could read it.
