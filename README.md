# The Family Daily

A guide for a nontechnical household member to set up a kitchen newspaper with Grok Bot, followed by a technical runbook for the bot doing the work.

The setup uses an always-on Mac, selected family calendars, email, iMessage, WhatsApp, and weather. The reader chooses which sources to connect, reviews the first edition, and can add an optional Hokku / Huessen EPF1301 frame.

## Files

- `index.html` contains the complete guide and styles inline. It does not fetch HTML fragments or require JavaScript.
- `assets/sample-board.svg` is a fictional newspaper example.
- `assets/architecture.svg` explains the flow from selected information to the Mac and optional frame.

Keep these files together for a local preview. No build step is needed. Older `assets/guide-a.html`, `assets/guide-b.html`, and `assets/site.css` files, if present, are not used by this revision; do not rebuild the page from those older fragments.

## Publication and scope

- Published guide: https://zalberico.com/family-eink-guide/
- Repository: https://github.com/zalberico/family-eink-guide
- Grok Bot: https://x.ai/bot
- Frame firmware and server: https://github.com/defl/hokku_epaper

Revised September 17, 2026. Product requirements were checked against the official documentation linked in the guide. This editorial revision does not represent an end-to-end hardware installation test. The runbook requires the implementing bot to verify actual access, data, scheduling, and frame behavior in the household's environment.
