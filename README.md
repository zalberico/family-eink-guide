# The Family Daily — Kitchen E-ink Board Guide

A public tutorial for setting up a newspaper-style family kitchen board on a **Hokku / Huessen 13.3″ Spectra 6** e-ink frame — by directing **Grok Bot** (Cursor / Grok Bot desktop agent with a computer) on a small always-on Mac or Pi, not by hand-building every script yourself.

**Live guide:** [https://zalberico.com/family-eink-guide/](https://zalberico.com/family-eink-guide/)

Also: [https://zalberico.github.io/family-eink-guide/](https://zalberico.github.io/family-eink-guide/)

## What’s in here

- `index.html` — long-form tutorial (GitHub Pages site root)
- `assets/guide-a.html` / `guide-b.html` — loaded sections (Grok Bot framing, collectors, copy-paste prompts)
- `assets/sample-board.svg` — fictional sample board mock (Alex & Sam; calendar + mail + chat cues)
- `assets/architecture.svg` — you → Grok Bot → pipeline diagram

## Framing

You buy the frame and keep a host online. You install Grok Bot, connect it to that machine, and tell the bot what you want. The bot installs Hokku help, writes the HTML newspaper, wires collectors (calendar, email, iMessage/WhatsApp, weather, optional reminders/invites), schedules editions, verifies convert + `show_next`, and iterates when something breaks. You approve purchases, logins, Wi‑Fi, and anything security-sensitive.

## Privacy

This repo teaches a **pattern**. It does **not** include real household schedules, Wi‑Fi secrets, LAN IPs, tokens, chat logs, or screenshots of a live board. Samples use Alex & Sam and placeholders (`YOUR_WIFI`, `192.0.2.x`, `private-PLACEHOLDER`).

## Upstream hardware / firmware

- [defl/hokku_epaper](https://github.com/defl/hokku_epaper)

## License

Tutorial text and fictional sample art in this repo: use freely for your own household setup. Hokku/Huessen firmware and server remain under their upstream licenses.
