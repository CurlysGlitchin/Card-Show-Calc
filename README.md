# 🃏 Card Show Calc

**A free, mobile-first offer calculator and full show-day tracker for trading card vendors.**

🌐 **Live site:** [curlysglitchin.github.io/Card-Show-Calc](https://curlysglitchin.github.io/Card-Show-Calc/index.html)

-----

## What It Does

Card Show Calc is a two-tool suite built for vendors who buy, sell, and trade Pokémon, One Piece, sports cards, and other trading cards at in-person shows.

**No app download. No account required. Works on any phone.**

-----

## Tools

### 📊 Free Calculator (`index.html`)

The public-facing tool — shareable with anyone.

- Add multiple cards to a running cart
- Instantly see **70%, 75%, and 80%** offer amounts for the full cart
- Optional **sales tax calculator** with a toggle (set your local rate)
- Enter your phone or email to unlock the full tracker
- Fully usable offline once loaded

### 📋 Full Show Tracker (`tracker.html`)

The gated tool — unlocked by entering a phone number or email.

- **Buy tab** — log cards you buy with % picker (70/75/80), see today’s totals and market value
- **Trade tab** — log cards you trade and track trade value given
- **Sale tab** — log cards you sell with sale price + cost basis, profit calculated automatically with live preview
- **Summary tab** — all-time stats across all show days: buys, trades, sales, margin retained, total profit
- Full **transaction log** grouped by show date
- **Dark mode toggle** — light mode default for outdoor shows, dark mode for evening events
- All data saved to browser localStorage — survives page refreshes and closing the tab

-----

## Features

- ✅ Mobile-first — built and tested on iPhone and Android (Brave, Safari, Chrome)
- ✅ No backend, no database — pure HTML/CSS/JS, hosted on GitHub Pages
- ✅ Persistent storage via localStorage — your show data stays put
- ✅ Email/phone collection via [Formspree](https://formspree.io) on unlock
- ✅ Google AdSense ready — slots in place, pending approval
- ✅ Outdoor-readable — high contrast light mode, large touch targets, 16px inputs (no iOS zoom)

-----

## Tech Stack

|Layer          |Choice                                 |
|---------------|---------------------------------------|
|Frontend       |Vanilla HTML, CSS, JavaScript          |
|Fonts          |Syne (display) + IBM Plex Mono (prices)|
|Hosting        |GitHub Pages                           |
|Form collection|Formspree                              |
|Ads            |Google AdSense (pending)               |
|Storage        |Browser localStorage                   |

No frameworks. No dependencies. No build step.

-----

## File Structure

```
Card-Show-Calc/
├── index.html          # Free public calculator
├── tracker.html        # Gated full show tracker
├── README.md           # You're here
```

-----

## Local Development

No build tools needed — just open the files directly in a browser.

```bash
git clone https://github.com/curlysglitchin/Card-Show-Calc.git
cd Card-Show-Calc
open index.html
```

Or use VS Code’s Live Server extension for hot reload.

-----

## Deployment

This project is deployed automatically via **GitHub Pages** from the `main` branch root.

Any push to `main` triggers a redeploy — typically live within 1–5 minutes.

-----

## Roadmap

- [ ] Google AdSense approval + live ad slots
- [ ] Custom domain (e.g. `cardshowcalc.com`)
- [ ] CSV export for show-day transaction log
- [ ] Show history — browse and compare past show days

-----

## About

Built by [@curlysglitchin](https://github.com/curlysglitchin) — a card show vendor who got tired of doing percentage math on the fly at show tables.

-----

## License

MIT — free to use, fork, and adapt.
