# BayesChat 1.0.7 — Release Notes

**Version:** 1.0.7  
**Since:** 1.0.6  
**Date:** August 2026

---

## Highlights

### 1. Smoother Settings scrolling
Scrolling Settings (and pages like Terms of Service) no longer hitch or jitter during fast inertial scrolls. The settings sheet is isolated from the live chat view so the chat WebView doesn’t steal frames while you scroll.

### 2. More reliable jump-to-bottom after status-bar jumps
Fixed a case where the floating jump-to-bottom control could flash a white screen after status-bar layout jumps.


# BayesChat 1.0.6 — Release Notes

**Version:** 1.0.6  
**Since:** 1.0.5  
**Date:** August 2026

---

## Highlights

### 1. Completely new rendering engine — much smoother scrolling, far less CPU
We rewrote how the chat is drawn and scrolled. Long conversations feel much smoother, streaming puts far less load on the device, and CPU use drops substantially — especially on replies with code, tables, or math.

### 2. Better prompt caching — much shorter Time to First Token (TTFT)
We improved prompt caching so more of your conversation can be reused on the next turn. On supported providers, Time to First Token (TTFT) — the wait before the first token shows up — is cut dramatically, especially after the first message in a session.

### 3. Redesigned reasoning and tool UI — quieter, less distracting
Reasoning and tool-call sections have a new, calmer look. They’re easier to ignore while you read the answer, and still easy to open when you want the details.

### 4. Unified Reasoning effort setting
There’s now one clear control for how hard the model should think. Set it in Settings or in a Chat Preset, and the same choice applies consistently across chats.

---

## Improvements

- **Standard iOS edge-swipe drawer** — open chat history with the familiar left-edge swipe instead of a custom gesture.
- **Finer font-size control** — more granular steps so you can dial text size more precisely.
- **Markdown export** — export a chat session as Markdown.
- **Export loading animation** — clear progress feedback while an export is preparing.
- **Rate the app** — quick link on the About screen.
- **iPhone portrait lock** — iPhone stays in portrait for a more consistent layout.
- **iPad orientation** — layout holds up correctly after rotating the iPad.

---

## Bug Fixes

- Fixed Chat Preset selection and deselection logic (including cases where a preset was cleared or not restored when starting a new chat or leaving a preset).
- Fixed iPad layout issues after orientation changes.

---

## Thank you

Thanks for using BayesChat.
