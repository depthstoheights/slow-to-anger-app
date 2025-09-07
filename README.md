# Slow to Anger — Depths to Heights

A **mobile-first, offline** app that helps you track triggers, calm your body, learn Scripture’s way, and choose holy responses when angry. Runs entirely from a single `index.html`.

- **Website:** https://depthstoheights.org  
- **Email:** depthstoheights@gmail.com  
- **Donate:** https://www.paypal.com/donate/?hosted_button_id=8GRE7B8C3TP2U  
- **Creator:** Made by Justin

---

## Features

- **Anger Tracker**
  - Log triggers, body sensations, intensity (1–10), responses, tags, outcomes
  - Weekly stats + inline line chart
  - Edit/delete with undo, filter by tag
  - Export `.txt` or copy list

- **Calming Prayers & Breathing**
  - Box breathing (4–4–4–4) with animated square + progress bar
  - **Voice chooser** (device SpeechSynthesis) with **preview**, **rate**, **pitch**, and **save default**
  - Play single prayers or all

- **Biblical Teaching**
  - Practical notes on Ephesians 4:26, James 1:20, Proverbs 15:1, Ecclesiastes 7:9
  - Quick prayers, safety reminder, helpful links

- **Redeem Your Reactions**
  - Guided 4-step exercise (Pause & Name → Story → Ask God → Choose Action)
  - Save plans; read them aloud using your chosen voice

- **Background Music**
  - Subtle generative plucks + echo (toggle on/off)

- **Privacy**
  - All data stored in **LocalStorage** only (no accounts/servers)

- **UI**
  - Distinct warm, light theme (terracotta + olive)
  - Persistent bottom nav: Home, Crisis, Resources, Info, About
  - Mobile responsive

---

## Installation

1. Save the provided code as **`index.html`**.
2. Open in any modern browser (Chrome, Edge, Safari, Firefox).
3. Optional: Install to phone  
   - **iPhone (Safari):** Share → *Add to Home Screen*  
   - **Android (Chrome):** Menu ⋮ → *Add to Home Screen*

> Note: Music starts after you tap the **Music** button (browser autoplay rules).

---

## Technology

- **HTML/CSS/JavaScript** (single file)
- **LocalStorage** for persistence
- **WebAudio** for background music
- **SpeechSynthesis** for narration

---

## Support

- Website: https://depthstoheights.org  
- Email: [depthstoheights@gmail.com](mailto:depthstoheights@gmail.com)  
- Donate: https://www.paypal.com/donate/?hosted_button_id=8GRE7B8C3TP2U

---

## License

Copyright © 2025 **Depths to Heights**
- Personal & ministry use permitted.
- Keep attribution intact. No resale.

---

## Testing Checklist

- [x] Single `index.html` only  
- [x] No alerts/confirm/prompts  
- [x] Bottom nav visible (Home, Crisis, Resources, Info, About)  
- [x] Info & About modals open/close  
- [x] PayPal link opens correctly  
- [x] Music toggle works (WebAudio)  
- [x] Voice picker preview + save; rate & pitch sliders work  
- [x] Tracker: save/edit/delete/filter/export/copy; stats & chart update  
- [x] Calming: prayers list works; box-breathing animates; play/stop works  
- [x] Exercises: save plans; read aloud; delete with undo  
- [x] Mobile responsive  
- [x] Crisis message is generic/global
