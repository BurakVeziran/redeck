<h3 align="center">
  <sub>
    <p align="center"><img src="src/assets/images/icon128.png" height="128" width="128"  alt="redeck icon"/></p>
  </sub>
  ReDeck Chrome Extension
</h3>
<p align="center">
ReDeck is a Chrome extension that turns X into a TweetDeck-style, multi-column workspace — directly at `x.com/redeck`.
</p>

<p align="center">
  <img alt="Chrome" src="/src/assets/images/chrome.svg" />
  <img alt="Manifest V3" src="/src/assets/images/manifest-v3.svg" />
  <img alt="TypeScript" src="/src/assets/images/typescript.svg" />
  <img alt="React" src="./src/assets/images/react.svg" />
</p>

<p align="center">
  <a target="_blank" title="Chrome Web Store Link of ReDeck extension" href="https://chromewebstore.google.com/detail/redeck-%E2%80%94-multi-column-das/kbipcnjpdpicihheehhcmjmgdlaffbfi">
    <img src="src/assets/images/chromeStoreBranding.svg" height="45" alt="Chrome Web Store Badge" />
  </a>
</p>

---

<p align="center">
  <img alt="screenshot" src="/src/assets/images/screenshot.png" />
</p>

## Why ReDeck?
X is noisy. ReDeck gives you control.

- Multi-column view without compromises
- Customize everything per column
- No tracking, no backend — your data stays local
- Fast, predictable, and built for heavy usage

Built for people who live on X.

## Features
### Columns & Layout
- Multi-column dashboard with drag-and-drop ordering
- Independent scrolling per column
- Sidebar navigation for quick jump/focus
- Built-in columns: Home, Following (chronological), Notifications, Explore
- Search, Post composer, Grok, Chat, and Custom URL support
- Add columns via right-click “Add to deck” from X links

### Column Controls
- Adjustable width (25–45rem)
- Title override and duplication
- Auto-reload (5–3600s) + manual refresh
- Back navigation and scroll-to-top
- Hide banner/top bar per column
- Persistent accent color (manual picker)
- Per-column visual configuration

### Tweets & Media
- One-click block and immediate tweet removal
- Automatic text expansion
- Download images and videos
- Full-screen image viewer
- Optional tweet enrichment (e.g. estimated revenue)
- Account labeling/tagging system

### Global Controls & Notifications
- Sleep mode with inactivity timer (0–60 min)
- Disable autoplay, adjustable text size, account switching
- In-app toast notifications

### Performance
- API rate-limit indicator (from response headers)
- Off-screen column suspension
- Smart keep-alive behavior
- Refresh recommendation for long sessions

### Privacy

ReDeck is local-first by design:

- No backend
- No tracking
- No analytics
- No data collection

All data is stored locally in your browser (IndexedDB via Dexie).

## Tech Stack
- Chrome Extension
- TypeScript + React 19
- Tailwind CSS + Radix UI
- Zustand + Immer
- Dexie (IndexedDB)
- dnd-kit

## Feedback
Bugs, ideas, or feature requests are welcome — please open an issue.
