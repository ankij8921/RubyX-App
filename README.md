# RubyX ✦ — Personal AI Assistant

Your personal AI, powered by Claude. Knows your goals, your fitness plan, your calendar, and everything you're working toward in 2026.

🔗 **Live app:** https://ankij8921.github.io/RubyX-App

---

## Features
- 💬 **Chat** — Full AI chat powered by Claude with your complete profile built in
- 📊 **Today** — Dashboard with water tracking, workout checklist, weight progress
- 🎯 **Goals** — All 2026 MLPs with progress tracking
- 📝 **Notes** — Persistent note-taking with search and auto-save
- 🎤 **Voice** — Speak to RubyX, get spoken replies
- 🩷 **Pink** — Because amber was not it

---

## Stack
- Single HTML file — no build step, no dependencies
- Claude API (claude-sonnet-4-20250514) via Anthropic
- Web Speech API for voice input/output
- localStorage for persistent notes, water tracking, API key
- GitHub Actions for auto-deploy on every push

---

## Updating RubyX
Every time a new `index.html` is pushed to `main`, GitHub Actions automatically redeploys to GitHub Pages within ~20 seconds.

To update from your Mac:
```bash
cd ~/RubyX-App
cp /path/to/new/RubyX.html index.html
git add index.html
git commit -m "✦ Update RubyX"
git push
```

Or just run:
```bash
./update.sh
```

---

## First-time Setup on iPhone
1. Open https://ankij8921.github.io/RubyX-App in Safari
2. Tap Share → **Add to Home Screen**
3. Enter your Anthropic API key once — saved permanently
4. Say *"Hey Siri, Open RubyX"* to launch hands-free

---

*Built with Claude · Maintained by Ankita Jain*
