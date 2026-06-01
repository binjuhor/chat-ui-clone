# Messaging App UI Clones

Pixel-perfect messaging app UI clones — single HTML files, zero dependencies.

## TODO

- [x] WhatsApp Web
- [x] Telegram Web
- [x] Zalo Web
- [x] Facebook Messenger Web

---

## WhatsApp Web Clone

A pixel-perfect WhatsApp Web UI clone.

### Demo

Open `whatsapp-web.html` directly in any modern browser. No server, no build step.

### Features

- **Dark theme** matching WhatsApp's color system (`#111b21`, `#00a884` accent)
- **Sidebar** — 10 mock conversations with avatars, timestamps, unread badges, online indicators
- **Filtering tabs** — All / Unread / Favorites / Groups
- **Search** — filters by chat name and message preview
- **Message bubbles** — sent (right, green) and received (left, gray) with triangular tails, timestamps, double-check read receipts (blue when read)
- **Group messages** — color-coded sender name labels
- **Emoji-only messages** — rendered at 32px
- **Emoji picker** — 39 emojis in an 8-column grid popup
- **Auto-resize textarea** — grows up to 140px, Enter to send
- **Typing indicator** — animated three-dot animation before simulated reply (1–2s delay)
- **Responsive** — single-panel mode on screens < 768px with back button

---

## Telegram Web Clone

A pixel-perfect Telegram Web UI clone.

### Demo

Open `telegram-web.html` directly in any modern browser. No server, no build step.

### Features

**Layout & Navigation**
- Dark theme matching Telegram (`#0f1923` deep bg, `#232e3c` sidebar, `#2481cc` accent)
- Fixed 340px sidebar + flexible main panel
- Filter tabs — All / Personal / Groups / Channels / Bots
- Search filters chat list by name and message preview
- Responsive — single-panel on screens < 768px with back button

**Chat List**
- 12 conversations — private chats, groups, channels, bots
- Avatars with color-coded initials, online status dots
- Unread count badges (muted variant), pinned chat indicators
- Verified badges for channels and bots

**Message Types**
- **Text** — regular bubbles with Telegram-style rounded corners and tail
- **Image** — photo placeholder with gradient thumbnail and overlay timestamp
- **Video** — video thumbnail with play button, duration badge, overlay timestamp
- **Audio / Voice** — waveform bars, play button, duration; click waveform to mark played
- **Sticker** — 72px emoji with transparent background
- **Incoming call** — green phone icon, duration
- **Outgoing call** — blue phone icon, duration
- **Missed call** — red phone icon, "Tap to call back"
- **Reply** — quoted message bar with author name
- **Forwarded** — forwarded-from label with arrow icon
- **System messages** — centered pill (e.g. "Alex joined the group")
- **Date separators** — centered date pills between message groups

**Input & Interactions**
- Auto-resize textarea (max 140px), Enter to send
- Mic icon when empty → Send icon when typing (toggle)
- Emoji picker popup — 39 emojis in 8-column grid
- Attach button (paperclip icon)
- Simulated typing indicator (three-dot bounce) → random reply after ~1–2s

### Conversations Included

| Name | Type | Notes |
|------|------|-------|
| Design Squad | Group | All message types demo |
| Telegram | Channel | Verified, pinned |
| Kristina Chen | Personal | Online |
| BotFather | Bot | Verified |
| Alex Petrov | Personal | — |
| Tech Talk | Group | Muted |
| Durov's Channel | Channel | Verified |
| Sarah Williams | Personal | Online |
| CryptoAlerts | Bot | Muted, 12 unread |
| Travel Buddies | Group | — |
| Marco Rossi | Personal | — |
| Hacker News Bot | Bot | Muted |

---

## Zalo Web Clone

A pixel-perfect Zalo Web (chat.zalo.me) UI clone.

### Demo

Open `zalo-web.html` directly in any modern browser. No server, no build step.

### Features

**Layout & Navigation**
- Light theme matching Zalo (`#f0f2f5` bg, `#006AF5` accent blue, white panels)
- Three-column layout: 64px nav strip + 320px chat list + flexible chat view
- Left nav strip — Chat, Contacts, Groups, Cloud, Settings icons (Zalo-style blue sidebar)
- Filter tabs — All / Unread / Groups
- Search filters chat list by name and message preview
- Responsive — single-panel on screens < 768px with back button

**Chat List**
- 12 conversations with Vietnamese names — personal, group, official accounts
- Color-coded avatars, online status dots
- Bold unread previews with unread count badges
- Timestamps (time for today, day name for older)

**Message Types**
- **Text** — rounded pill bubbles; sent light-blue (`#dbeeff`), received white with border
- **Image** — gradient photo placeholder with overlay timestamp
- **Video** — gradient thumbnail with centered play button, duration badge
- **Audio / Voice** — waveform bars + play button; click waveform to mark played
- **Sticker** — 72px emoji with transparent background
- **Incoming call** — green phone icon, duration
- **Outgoing call** — blue phone icon, duration
- **Missed call** — red phone icon, "Tap to call back"
- **Reply** — quoted message bar with author name and blue accent border
- **Forwarded** — forwarded-from label with arrow icon
- **System messages** — centered pill (e.g. "Lê Thị Hoa joined the group")
- **Date separators** — centered date pills

**Input & Interactions**
- Input pill (rounded container), auto-resize textarea (max 120px), Enter to send
- 👍 Like button when empty → Send arrow when typing
- Emoji/sticker picker popup — 39 emojis in 8-column grid
- Attach, image, sticker buttons in input bar
- Reaction bar on hover (❤️😂😮😢😡👍) — click to add reaction badge
- Simulated typing indicator → Vietnamese reply after ~1–2s

### Conversations Included

| Name | Type | Notes |
|------|------|-------|
| Dev Team VN | Group | All message types demo |
| Nguyễn Minh Khoa | Personal | Online, 1 unread |
| Trần Thị Lan | Personal | — |
| Zalo Official | Channel | Official account |
| Phạm Quốc Bảo | Personal | Online |
| Backend Team | Group | — |
| Lê Thị Hoa | Personal | Online |
| AI Club VN | Group | 7 unread |
| Hoàng Văn Nam | Personal | — |
| Zalo Pay | Channel | Official account |
| Võ Thị Thu | Personal | — |
| Ngô Minh Đức | Personal | — |

---

## Facebook Messenger Web Clone

A pixel-perfect Facebook Messenger Web UI clone.

### Demo

Open `messenger-web.html` directly in any modern browser. No server, no build step.

### Features

- **Dark theme** matching Messenger (`#1c1c1c` bg, `#0084ff` blue accent)
- **Sidebar** — 8 mock conversations with avatars, unread indicators, online status dots
- **Active Now strip** — horizontal scrollable row of currently online contacts
- **Search** — filters chat list by name and message content
- **Fully-rounded pill bubbles** — sent (blue, right), received (gray, left) with consecutive-chain radius collapsing
- **Group messages** — color-coded sender name labels
- **Emoji-only messages** — rendered at 36px with transparent background
- **Message reactions** — hover any bubble to open ❤️😂😮😢😡👍 reaction bar; click to toggle
- **Seen indicator** — contact avatar + "Seen" appears under your last read message
- **Typing indicator** — animated three-dot bounce before simulated reply (~1–2s)
- **Emoji picker** — 39 emojis in 8-column grid popup
- **Auto-resize textarea** — grows up to 120px, Enter to send
- **Like/Send toggle** — 👍 thumb when input is empty, send arrow when typing
- **Responsive** — single-panel mode on screens < 768px with back button

---

## Stack

| Concern | Solution |
|---------|----------|
| Markup | Vanilla HTML5 |
| Styles | CSS custom properties (no framework) |
| Logic | Vanilla JavaScript (no libraries) |
| Icons | Inline SVG |
| Fonts | System font stack (`-apple-system`, `system-ui`) |

## Project Structure

```
whatsapp/
├── whatsapp-web.html    # WhatsApp Web clone
├── telegram-web.html   # Telegram Web clone
├── zalo-web.html       # Zalo Web clone
└── messenger-web.html  # Facebook Messenger Web clone
```
